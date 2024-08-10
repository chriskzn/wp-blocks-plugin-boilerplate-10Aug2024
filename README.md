# wp-blocks-plugin-boilerplate-10Aug2024
WordPress Blocks Plugin Boilerplate as of 10 August 2024

# 1. This is the content of .editorconfig
# This file is for unifying the coding style for different editors and IDEs
# editorconfig.org

# WordPress Coding Standards
# https://make.wordpress.org/core/handbook/coding-standards/

root = true

[*]
charset = utf-8
end_of_line = lf
insert_final_newline = true
trim_trailing_whitespace = true
indent_style = tab

[*.{yml,yaml}]
indent_style = space
indent_size = 2


# 2. This is the content of .eslintrc
{
    "extends": [ "plugin:@wordpress/eslint-plugin/recommended-with-formatting", "prettier" ]
}

# 3. This is the content of .prettierrc
"@wordpress/prettier-config"

Above files belong in the root of the plugin folder.
