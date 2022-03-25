# qb-vault-npstyle
Edited Version qb-vault NP Style


Install:

copy qb-vault and iyc-input in your resources files

ensure 2 scripts in your server.cfg

ensure qb-vault
ensure iyc-input

if you need use my input for another script you should use it like this

local mdialog = exports['iyc-input']:ShowIycInput({
        header = "NewPassword",
        submitText = "Submit",
        inputs = {
            {
                text = "", -- text you want to be displayed as a place holder
                name = "", -- name of the input should be unique otherwise it might override
                type = "", -- type of the input
                isRequired = true -- Optional [accepted values: true | false] but will not submit the form if no value is inputted
            }
        },
    })

small perview:
https://cdn.discordapp.com/attachments/938930956033728532/956886050620457040/unknown.png
