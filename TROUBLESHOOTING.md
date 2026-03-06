# Troubleshooting

## IntelliJ IDEA: "Too many non-blocking read actions submitted at once"

### Error

```
java.lang.Throwable: Too many non-blocking read actions submitted at once.
Please use coalesceBy, BoundedTaskExecutor or another way of limiting the
number of concurrently running threads.
```

This error originates from `FlutterPluginsLibraryManager.updateFlutterPluginsImpl` in the IntelliJ Flutter plugin. It occurs when the IDE submits too many concurrent non-blocking read actions during project scanning.

### Common Causes

1. **Flutter plugin scanning a non-Flutter project** — If you have the Flutter/Dart plugin enabled in IntelliJ, but the project is not a Flutter project, the plugin may repeatedly attempt to scan and update plugin libraries unnecessarily.
2. **Duplicate or confusingly-named files** — Files with invisible Unicode characters in their names (e.g., Left-to-Right Mark U+200E) can cause the IDE's file indexer to behave unexpectedly, triggering redundant read actions.
3. **Outdated IntelliJ or Flutter plugin version** — Older versions may lack proper coalescing (`coalesceBy`) for non-blocking read actions.

### Solutions

1. **Disable the Flutter plugin** (if not needed):
   - Go to **File → Settings → Plugins**
   - Search for **Flutter** and **Dart**
   - Uncheck/disable them and restart the IDE

2. **Update IntelliJ IDEA and plugins**:
   - Go to **Help → Check for Updates**
   - Update the Flutter and Dart plugins to the latest versions

3. **Invalidate caches and restart**:
   - Go to **File → Invalidate Caches / Restart**
   - Select **Invalidate and Restart**

4. **Clean up project files**:
   - Remove any files with invisible Unicode characters in their names
   - Ensure there are no duplicate files that could confuse the file indexer
