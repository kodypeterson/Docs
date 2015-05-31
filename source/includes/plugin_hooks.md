# Plugin Hooks

**Available for all supported games:**  
[![Rust](images/icon-rust.png)](rust.html)
[![Rust Legacy](images/icon-legacy.png)](legacy.html)
[![7 Days to Die](images/icon-7dtd.png)](sdtd.html)
[![Reign of Kings](images/icon-rok.png)](rok.html)

## Init

``` csharp
void Init()
{
    Puts("Init works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called when the plugin is being loaded
 * Other plugins may or may not be present, dependant on load order
 * Other plugins WILL have been executed though, so globals exposed by them will be present

## LoadDefaultConfig

``` csharp
void LoadDefaultConfig()
{
    Puts("LoadDefaultConfig works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called when the config for the plugin should be initialized
 * Only called if the config file does not already exist

## OnFrame

``` csharp
void OnFrame()
{
    Puts("OnFrame works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Placeholder

## Unload

``` csharp
void Unload()
{
    Puts("Unload works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called when the plugin is being unloaded

## OnPluginLoaded

``` csharp
void OnPluginLoaded(Plugin pluginName)
{
    Puts("OnPluginLoaded works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called when specified plugin has been loaded

## OnPluginUnloaded

``` csharp
void OnPluginUnloaded(Plugin pluginName)
{
    Puts("OnPluginUnloaded works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called when specified plugin has been unloaded