#cfn-yaml-vs:
#YAML CloudFormation Template Snippet Set for Visual Studio Code


cfn-yaml is a vscode user snippet file for cloudformation yaml syntax.

The snippet set is created from the AWS documentation as the master defintion for the YAML content and includes a comment within each snippet referencing back to the [AWS Reference documentation pages](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html) for easy right-click opening of the documentation related to the snippet.  This is obviously included to make it quick and easy to get back to the documentation related to the function being configured.

This snippet set was inspired by cform package and is the vscode version of cfn-yaml that was created for Sublime Text 3.

Should you wish to remove the documentation links after you've finished creating your template, then simply do a search and replace with regex enabled finding `#AWS-DOC.*\n` and replace with `nothing`

```
Usage:

# Easiest way to get to use these snippets is simply to clone this repo and copy the yaml.json file to ~/.config/Code/User/snippets/yaml.json and set your document type to yaml.
# Press Ctrl_Space to show snippets and search by resource name.

git clone https://github.com/Narrowbeam/cfn-yaml-vs.git
```
Please note that these are still a work in progress and may evolve over time to include inter-field tabbing support etc.

If you find any issues or want to expand the snippet set, just create a pull request :-)