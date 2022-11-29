sci.loadstring(code, env)
===
Loads a string with custom enviroment.

Param code - `string` - The code.

Param env - `table` - The enviroment for the code.

Return `function` - The function to run the code. (`loadstring("YOUR_CODE_HERE", {YOUR_ENV_HERE})()`)