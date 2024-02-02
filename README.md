# VSCodeSnippetsForUnity
Convenient snippets for my most used code blocks.

## Snippet List

### Debugs
- `debug` for `Debug.Log($"Hello, World");`
- `debugw` for `Debug.LogWarning($"Warning");`
- `debuge` for `Debug.LogErro($"Error");`
- `debugg` for `Debug.Log($"{nameof(var)}: {var});`

### Coroutines
- `corupdate` for creating a looping coroutine
- `correstart` for restarting a looping coroutine; only works with [RestartCoroutine()](https://github.com/BlokyMose/PlugRMK/blob/master/UnityUti/GameUtility/CoroutineUtility.cs) in plugin [PlugRMK](https://github.com/BlokyMose/PlugRMK)
- `cordelay` for creating a delayed coroutine
- `eventtri` for adding EventTrigger and entries to an image component

### Attributes
- `sf` for `[SerializeField]`
- `sb` for `[Serializable]`
