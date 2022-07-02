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

| yamlCallIt           |quickToRead(may not exact)  |  sytax      | howToUse   | 
| ----                 | -----                      | -----       | ---------  | 
| comment              |                            |    \#       |            |          
| node denote          | declare variable           |   \&        |            |   
| Literal Style        | keep line breaks of a string|   \\       |after ": "  | 
|                      |                            |             |            | 
|    signal the start of a document   |                            |    ---      |      top of file   | 
|    signal the end of a document   |                            |    ...      |      bottom of file   | 
|    string value |                            |    "" or '' or without quotes      |      string value   | 
|    boolean value |               |    true/on/yes or false/off/no      |      string value   |
|    lists |              |   [-a,-b,-c]      |      list value   |


|Type      | yamlCallIt           | weCallIt  | limitation |
|----      | ----                 | --------- | ---------- |
|defination       | stream               |    file   |            |
|defination       | document             |    file   | file content  |
|defination       | node                 |    node   |   can call repeat node     |
|defination       | directives                 |    node   |   can call repeat node     |

