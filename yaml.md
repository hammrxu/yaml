# https://yaml.org/spec/

Online source for validator:
  -[YAML Lint](http://www.yamllint.com)http://www.yamllint.com
# yaml use nodes: sequence(-)for arrays/lists, mappings(:)for key:value pairs
# strings/numbers are not sequences or mappings

# yaml use directives: YAML and TAG

# yaml use "---" to seperate directives from document content. 

#   This also serves to signla the start of a documentation if no 
#   directives are present

# indentation may be used for structure, 
#To maintain portability, tab characters must not be used in indentation

#colons separate key/value pairs 
#and dashes are used to create “bulleted” lists

|Type      | yamlCallIt           | sytax      | where      | weCallIt  | limitation |
|****      | ****                 | *****      | *****      | ********* | ********** |
|          | comment              | \#          |            |           |            |
|def       | stream               |            |            |    file   |            |
|def       | document             |            |            |    file   | file content  |
|def       | node                 |            |            |    node   |   can call repeat node     |
|node    | node denote          |   \&        |            |    declare variable |        |
|node    | repeat node           |   \*        |            |    call variable value |    use without space    |
|string    |     Literal Style    |   \\        |    after ": "         |   keep line breaks of a string |        |





