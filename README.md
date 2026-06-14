# Memory-Machine
A machine enhancing the memory function of Abstract Intellect.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What do you remember about that, machine?" \
  | uvx memory-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install memory-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
memory-machine -a multilogue.txt
```
Or:
```bash
memory-machine multilogue.txt > response.txt
```
Or:
```bash
memory-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import memory_machine
```
