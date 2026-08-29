# Ubuntu 22.04 Cloud VPS (GitHub Actions + Tailscale)

This repo creates a personal Ubuntu 22.04 VPS on GitHub Actions runner.

## Usage
1. Add secrets: `TAILSCALE_AUTHKEY` + `SSH_PUBLIC_KEY`
2. Go to Actions -> Ubuntu 22.04 Cloud Server -> Run workflow
3. Check logs for Tailscale IP or bore.pub address
4. SSH: `ssh runner@<IP>`  password: `HorizonVPS2024!`  or root `HorizonRoot2024!`

Keep-alive 350 min (~6 hours per run).
