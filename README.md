# Config file details:
    **Environment**

    **Root**


# Difference between config and plugin
    1. its the whole config file which can be shareable and need to use in extends property
    2. Plugin is set of custom rules which first need to add in plugins and then mentioned it in rules as there could be lots of custom rules. Plugin can also shared config with set of rules.
    
# Global
    Global variable can be identified through here. Lets say require is global if it mentioned in config and set false it wont throw error

# Parser options:
   ## Eslint parse javascript code to AST and than linting.
         ### ecmaVersion: this define the support for version. Which means it will support linting for that ecma version. Lest say es2015 
         doesn't support async await. So if somehow ecmaVersion set to this than in code it will throw error.
