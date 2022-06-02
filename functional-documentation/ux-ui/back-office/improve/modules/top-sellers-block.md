# Top-sellers block

## Description

This is the main configuration page for the module.

![](<../../../../../.gitbook/assets/Screenshot 2022-05-30 at 17-26-07 Module Manager • test.png>)

### Front-Office

The module when enabled displays list of top-sellers of the shop at the main page at the bottom.

## Components description

The module at the top has 4 buttons:

* Back
* Translate
* Check update
* Manage Hooks

#### 1 Component is present within the module settings:

* Products to display

| Description              | Value                                                         | Error message                                                                |
| ------------------------ | ------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Mandatory                | No                                                            | -                                                                            |
| Allowed/Forbidden values | When anything apart numbers is saved, resets the value to "0" | Not an error message, but when saved shows "The settings have been updated." |
| Help text                | "Determine the number of product to display in this block"    | -                                                                            |

## Behavior

#### Top buttons - Call to action

1. **Back**

When pressed redirect back to the module manager (Modules > Module manager).

**2. Translate**

When pressed, a pop-up opens with a drop-down, from which it is possible to select one of the languages installed on the shop to translate the module.

**3. Check update**

Checks for updates on the module.

**4. Manage hooks**

When pressed redirects to the (Design > Positions).

#### Save - Call to action

* If all fields are input correctly, when pressed will show: "The settings have been updated.". If some of the fields are incorrect or empty, will show an error according to the mistake.

## Configuration

This section has a checkbox for:

* Activate module for this shop context: all shops.

By default the checkbox is marked.

## Error messages

No error messages are present for this module, only a message "The settings have been updated." when settings are changed.
