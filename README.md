
# Install the itcl ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_itcl

# Clone the itcl ansible role. 
git clone git@github.com:computate-org/computate_itcl.git ~/.ansible/roles/computate.computate_itcl
cd ~/.ansible/roles/computate.computate_itcl
```

# Run the itcl ansible playbook to install itcl locally. 

```bash
ansible-playbook install.yml
```

