# Introduction 


# With a job

When outputing a variable from a step, it can be referenced in scripts in subequent steps in the same job with the syntax:
$(stepName.variableName)

isOutput is not case sensitive




trying to pass a variabe into a template as a parameter:

$[variables.templateParam] 
results in the literal string "$[variables.templateParam]" being passed to the template, not the value of the variable.

passing as $(variables.templateParam) works as expected