# .editorconfig

# EditorConfig helps maintain consistent coding styles across editors and IDEs

root = true

[*]
charset = utf-8
end_of_line = lf
insert_final_newline = true
trim_trailing_whitespace = true

[*.md]
# Markdown: allow trailing spaces for line breaks
trim_trailing_whitespace = false
max_line_length = off

[*.{js,ts,css,scss,py}]
indent_style = space
indent_size = 4

[*.yml]
indent_style = space
indent_size = 2

