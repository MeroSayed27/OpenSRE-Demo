# PowerShell Setup Logs – OpenSRE Demo

## Installation & Onboarding
- Ran `opensre onboard` in Windows PowerShell
- Switched provider from Anthropic → OpenAI
- Added OpenAI API key (gpt‑5.4 model)
- Skipped integrations for now

## Investigation Run
```powershell
& "C:\Users\A1\.local\bin\opensre.exe" investigate -i "C:\Users\A1\OneDrive\Desktop\datadog_k8s_alert.json"
