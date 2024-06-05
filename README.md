# cli-demo
A demo of using GPTScript to interact with various CLIs throug a chat interface

This GPTScript will launch a chat assistant that's integrated with two common developer CLIs: `gh` (the GitHub cli) and `kubectl` (the Kubernetes cli).

This **DOES NOT** install or configure the CLIs. You must do that yourself.

To launch, run:
```
gptscript github.com/gptscript-ai/cli-demo
```
or clone this repository and run the local file:
```
gh repo clone gptscript-ai/cli-demo
cd cli-demo
gptscript ./agent.gpt
```
