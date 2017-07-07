# PyCharm Live Templates for OpenERP 

### Install

```sh
cp OpenERP.xml ~/.PyCharmXX/config/templates/
```

### Use

Inside your OpenERP files: XML views, Python files

Press **Ctrl + J** to insert the template

### Existing features (in parentheses the keyword to use inside the PyCharm file):

#### Python

- Creating `__terp__.py` (`__terp__`)
- Creating a function field (`ff`)
- Creating a write function field (`ff_inv`)
- Creating a search function field (`ff_search`)
- Creating the name_get function (`name_get`)
- Creating the function name_search (`name_search`)
- Creating an object (`osv_class`)
- Returning a report from a function (`return_report`)
- Return a window from a function (`return_window`)

#### XML

- Creating the `<openerp> <data>` tags (`openerp_tags`) 
- Creating an action (`ir_action`)
- Creating a view (`ir_ui_view`)
- Creating a menu (`menuitem`)
- Creating a security group (`security`)
- Creating a shortcut from one object to another (`shortcut`)
- Defining a wizard (`wizard`)
