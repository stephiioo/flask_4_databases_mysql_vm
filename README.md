# flask_4_databases_mysql_vm


## azure virtual machine set up process:


### step 1: open up microsoft azure and sign in


### step 2: type in Virtual Machine into the search bar, click on it and when it opens up, hit "create" and then of the two options presentes, click "virtual machine"


### Step 3: configure the VM appropriately so that it has the cost option of $15.11


#### some key configurations to note:

#### resource group: i saved my vm to a previously created resource group called "stephanie-504"

#### region: us east

#### image: ubuntu server gen 2

#### size: standard b1ms 1 vcpu 2 gib

#### authetication type: click password and enter preferred username and password

#### vm network ports: http (80), https (443), ssh (22)

#### enable auto-shutdown at set to 11:59pm east (us & canada)


### step 4: rveiew and create vm

## VM setup process:

### step 1: open cloud shell

### step 2: in the cloud shell terminal, enter:

#### - pwd

#### - ssh sogbebor@52.186.170.225 (which is the ip address for the azure VM)

#### - type "yes", hit enter, then type in your password and hit enter

#### your cloud shell should now say "sogbebor@mysql-vm:~$:

### step 3: type "sudo apt-get update"

### step 4: type "sudo apt install mysql-server mysql-client" then type "Y" when prompted

### step 5: type "sudo MySQL" which will allow the terminal to display "MySQL>"
