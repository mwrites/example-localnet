# **Hello Clockwork Example + Clockwork v1.4 **

### Builds:
- solana-cli 1.14.12 (src:979792ba; feat:4145199441)
- avm 0.26.0
- Clockwork 1.4.4 (branch v1.4)


### Steps
0. sh -c "$(curl -sSfL https://release.solana.com/v1.14.12/install)" 
1. clockwork-v1.4/scripts/build-all.sh clockwork-v1.4
2. clockwork-v1.4/bin/clockwork localnet
3. ./deploy.sh localnet
4. (optional) anchor test --skip-local-validator
