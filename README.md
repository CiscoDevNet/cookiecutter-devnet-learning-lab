# cookiecutter-devnet-learning-lab

A `cookiecutter` template for creating DevNet Learning Labs quickly

If you are creating an entirely new module, you may want to start here:
https://github.com/CiscoDevNet/cookiecutter-devnet-learning-module

If you are working in an existing module, you can add an additional lab to that
module by running the following in the `labs` folder of your existing module.

## How to use this template

Make sure you install the Python `cookiecutter` library, then use this command to run through template prompts:
```
    $ cookiecutter https://github.com/CiscoDevNet/cookiecutter-devnet-learning-lab
```


## Sample workflow

```
➜  my-awesome-learning-module cd labs
➜  labs ls
my-awesome-learning-lab
➜  labs pwd
/tmp/Projects/my-awesome-learning-module/labs
➜  labs cookiecutter gh:ciscodevent/cookiecutter-devnet-learning-lab   
lab_name [my-awesome-learning-lab]: another-lab
lab_title [lab title]: another title
lab_slug [One sentence description of the learning lab.]:
lab_tag [One word or short phrase to categorize this lab.]: 
author_name [John Smith]:
author_email [jsmith@company.com]:
➜  labs
➜  labs ls
another-lab             my-awesome-learning-lab
```

## Don't have cookiecutter?

Install it with this command, typically inside a virtual environment:
   ```
   $ pip install cookiecutter
   ```
