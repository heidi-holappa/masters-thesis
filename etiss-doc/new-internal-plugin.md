# Creating a new internal plugin

- The header for the plugin should be placed in the path `include/etiss/IntegratedLibrary`
- The cpp file should be placed at `src/IntegratedLibrary`
- Update `src/IntegratedLibrary.cpp`:
  - include your plugin's header
  - update `ETISSINCLUDED_countPlugin` to include the new plugin (increment by 1)
  - include your plugin's name to `ETISSINCLUDED_namePlugin`
  - include case to `ETISSINCLUDED_createPlugin`
