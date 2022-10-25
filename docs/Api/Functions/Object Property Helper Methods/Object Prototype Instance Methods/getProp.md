# Object.prototype.getProp
**function, instance**
Get a deep property from an object, or return null.

**NOTE**: This is a wrapper for [GetDeepProperty](../Static%20Api%20Methods/GetDeepProperty.md).
## *Params*
- **propertyPath** *(string|array(string))* Array of keys, or dot seperated propery key string.
- **defaultValue** *(any|function)* The default value to use if this value wasn't found. If a function is passed in it will be called to fetch the value.