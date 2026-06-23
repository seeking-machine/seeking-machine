# Seeking-Machine
A Machine that is seeking the Truth.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: You need to seek the real answer, machine." \
  | uvx seeking-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install seeking-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
seeking-machine -a multilogue.txt
```
Or:
```bash
seeking-machine multilogue.txt > response.txt
```
Or:
```bash
seeking-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import seeking_machine
```
