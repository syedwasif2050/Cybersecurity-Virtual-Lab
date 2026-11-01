# Cybersecurity Virtual Lab Setup (Phase 1)

## Environment Details
- **Base OS:** Windows (Host)[cite: 5, 21]
- **Hypervisor:** Oracle VirtualBox[cite: 4, 19]
- **Attacker VM:** Kali Linux[cite: 4, 19]
- **Network Mode:** Custom NAT Network (`NatNetwork`, `10.0.0.0/24`)[cite: 4, 19]
- **Static IP:** `10.0.0.2/24` (Gateway: `10.0.0.1`)[cite: 4, 8, 19]

## Verification Proofs
### 1. Static IP Configuration (`ip a`)
![IP Config](image_name_1.png)[cite: 8]

### 2. Connectivity Test (`ping 10.0.0.1`)
![Ping Test](image_name_2.png)[cite: 9]
