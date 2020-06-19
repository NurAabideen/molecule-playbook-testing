### Steps of using Molecule

1. first run $ molecule init scenario 
2. edit the files under default/ such as converge.yml, molecule.yml verify.yml
3. make sure the image and privilege are setup correctly
4. next run $ molecule converge
5. Make sure the tests are either included with the playbook or under verify.yml
6. verify.yaml lets you verify the task without running the whole setup.
7. add - fail: in the mail.yml to stop the 
