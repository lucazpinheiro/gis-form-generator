## basic structure for json config file


### input field
```
{
    "inpytType": "text" or "number" or "checkbox" or "radio",
    "label": string,
    "valueName": string, // name to refer to this value on backend
    "isRequired": true or false,
}
```

### select field
```
{
    "label": string,
    "valueName": string, // name to refer to this value on backend
    "options": [
        {
            "optionValue": string,
            "optionText": string,
            "isSelected": true, // this propertie can only exist in one element of the options array
        },
        ...
    ]
    "isRequired": true or false,
}
```

[input types reference](https://www.w3schools.com/html/html_form_input_types.asp)


-----------
```
{
    "name": string,
    "author" string,
}
```
