dotnet-framework Cookbook
=========================
Installs .NET Framework 4.5.2 Multi-tageting pack. 

Requirements
------------
Runs on windows.

e.g.
#### packages
- `chocolatey` - dotnet-framework needs chocolatey to install packages.

Attributes
----------
None.

Usage
-----
Just include `dotnet-framework` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[dotnet-framework]"
  ]
}
```

Contributing
------------
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Ivan Li
