# Scratchers: PulseChain Onboarding Through Physical Cards
*A Community White Paper – Draft v1.1*

---

## 1. Introduction
PulseChain is building momentum, but onboarding new users remains one of the biggest challenges. Most airdrops and giveaways are digital-only, making them vulnerable to bots and failing to create real connection.

**Scratchers** changes this by introducing **physical scratch-off cards** that are:
- Community-sponsored and funded in PLS.
- Fun, familiar, and easy to understand.
- Fully transparent and provable on-chain.

Each Scratchers card gives its holder:
- A **starter voucher** of PLS.
- A **small faucet drip** so they can pay gas.
- A **raffle entry** for the batch prize pool.

To keep value flowing toward **real, interested users**, each card also has a **redemption expiry**. If it isn’t redeemed in time, the funds are **recycled** back into the system for future batches.

Scratchers can optionally plug into **ProveX**, a ProofFi-style attestation layer, to verify off-chain receipts, donations, and batch behavior — making the whole system **auditable end-to-end**.

This makes onboarding **simple, tangible, and exciting** — bridging the physical and digital worlds.

---

## 2. Why Scratchers?
- 🎟 **Fun & Familiar** – Scratch-off cards are understood everywhere.  
- 🚫 **Anti-Bot** – Only someone holding the card can redeem it.  
- 🧾 **Transparent** – All funds and packaging costs are tracked on-chain, with receipts uploaded for verification.  
- 🔄 **Sustainable** – Surplus funds and **unredeemed allocations** can be recycled into a buffer pool to stabilize and refuel future batches.  
- 🌍 **Scalable IRL** – Cards can be mailed, handed out at meetups, or distributed at events.  
- 🛡 **Proof-Backed (with ProveX)** – Optional integration with ProveX can attest that **off-chain evidence** (receipts, shipping docs, event records) matches **on-chain flows**, keeping sponsors and ambassadors accountable.  

---

## 3. How It Works

### 3.1 Sponsors Fund a Batch
Community members contribute PLS. Each card requires:
- **100,000 PLS** for packaging (paid to vendor).  
- **100,000 PLS** for voucher value (locked in BatchVault).  
- **10,000 PLS** for raffle pot (locked in RaffleVault).  

👉 Example: A 1,000-card batch = 210M PLS.

### 3.2 Cards Are Printed
- Each card contains:  
  - **Hidden scratch code** → redemption proof.  
  - **Unique raffle ticket number** → for batch drawing.  
  - **QR code** → links to redemption dApp.  

### 3.3 Redemption Flow
1. Scratch card → reveal code.  
2. Scan QR → open redemption dApp.  
3. Connect wallet + enter code.  
4. Smart contract verifies → user receives:  
   - **100k PLS voucher value**.  
   - **100 PLS faucet drip** (if wallet is empty).  
   - **Raffle ticket activation**.  

### 3.4 Batch Raffle
- Each redeemed card = one raffle entry.  
- At batch cutoff, contract runs a **provably fair on-chain draw**.  
- **One winner** per batch receives the full raffle pot.  
- Winning ticket and wallet are displayed publicly on the dApp.  

### 3.5 Redemption Expiry & Recycling
- Each card has a **redemption deadline** (for example, 60–90 days from batch activation).  
- If a card is **not redeemed by the deadline**, its **unused voucher and raffle allocation** remain in the BatchVault and are **released back into the system** instead of staying permanently locked.  
- By default, these reclaimed funds are:  
  - **Recycled into the Buffer Pool** to support future batches, or  
  - Optionally earmarked for **refill batches** targeted at new recipients.  
- This ensures that value is continuously redirected toward **people who actually redeem and engage** with PulseChain, rather than being stuck on lost or forgotten cards.  

---

## 4. Packaging Costs & Surplus Buffer

### 4.1 Receipts Required
- Ambassadors (batch operators) must **upload receipts** (invoices, shipping docs) to IPFS.  
- Vendor payouts reference these receipt hashes on-chain.  
- Sponsors and the community can audit costs at any time.  

With **ProveX integration**, these receipts and document hashes can also be:
- **Bundled and attested off-chain** (e.g., totals, vendor names, dates).  
- **Linked to on-chain attestations** that say whether the claimed amounts and vendors match the rules for that batch.  

### 4.2 Budget & Buffer
- Each card has a **100,000 PLS budget allocation** for packaging.  
- If actual costs are **less**, the surplus flows into a shared **Buffer Pool**.  
- If costs are **more**, the Buffer Pool is tapped first. If still short, sponsors top-off.  

### 4.3 Benefits
- Creates a **transparent record** of real-world costs.  
- Ensures **future batches** can smooth out small funding gaps.  
- Builds **confidence** that every PLS is documented and accounted for.  
- With ProveX, the community can see **which batches and ambassadors are fully “proof-verified”** for both on-chain and off-chain behavior.  

---

## 5. Proof-of-Physical-Distribution (PoPD)
- Primary PoPD = scratch code itself. Only someone with the card can redeem.  
- Optional enhancements for future phases:  
  - Serial numbers for tracking.  
  - NFC/QR validation layers.  
  - Ambassador bounties tied to unique redeemers.  

ProveX can extend PoPD by:
- Attesting that **card ranges, serials, or NFC tags** used in a batch match the batch definition.  
- Verifying that **distribution events** (meetups, mail-outs, conferences) have associated evidence (photos, lists, shipping logs) linked to that batch.  

---

## 6. Governance (DAO-Lite for MVP)
Sponsors can vote on adjustments for **future batches**, including:
- Voucher size (default: 100,000 PLS).  
- Raffle contribution (default: 10,000 PLS).  
- Packaging budget (default: 100,000 PLS).  
- Surplus allocation rules (default: 100% to Buffer Pool).  
- **Redemption expiry window** (e.g., 60 or 90 days).  
- **Recycling rules for unredeemed allocations** (e.g., 100% to Buffer Pool or split between Buffer Pool and special “refill” batches).  
- **Use of ProveX verification** (e.g., which checks are required before ambassador/vendor payouts).  

Over time, this “DAO-lite” model can evolve into a more robust ProofFi-style governance layer that enforces **minimum transparency standards** for any batch to be considered “Scratchers official.”

---

## 7. Benefits

### For Sponsors
- Direct, transparent impact on PulseChain adoption.  
- All funds verifiable on-chain.  
- Voting power to shape the system.  
- With ProveX, an extra layer of **proof-backed accountability** for how donations are used.  

### For Recipients
- Free starter funds and gas.  
- A fun, tangible entry into crypto.  
- A chance to win a raffle prize.  
- Greater confidence that **the system is fair** and is being watched by an independent attestation layer.  

### For the Ecosystem
- More wallets, more activity, more growth.  
- A repeatable onboarding model.  
- A “fun layer” for marketing, meetups, and events.  
- **Capital efficiency over time** as unredeemed allocations are recycled toward active users.  
- A live example of a **ProofFi-aligned dApp** using ProveX for real-world transparency.  

---

## 8. Roadmap
- **MVP (Season 1):** Batch funding, scratch-off redemption, faucet drip, per-batch raffle, surplus buffer, basic redemption expiry & recycling, and an initial ProveX integration concept (attestations for receipts and batch flows).  
- **Season 2:** Collectible editions, sponsor leaderboards, optional ambassador bounties, basic ProveX “verified batch” badges in the UI.  
- **Season 3:** Retail tie-ins, advanced PoPD (NFC, QR layers), community rewards, richer ProveX checks (raffle fairness, recycling correctness, and donation accounting).  
- **Season 4:** Governance expansion, tokenized incentives ($SCRATCH), deeper ProofFi standard alignment for Scratchers and other ecosystem dApps.  

---

## 9. Optional ProveX Integration (ProofFi Layer)

Scratchers can operate as a standalone project, but it can also be a **flagship ProofFi use case** by integrating with **ProveX**, an attestation engine that verifies:

- **Off-chain evidence**  
  - Invoices, shipping docs, event photos, distribution logs.  
  - Stored on IPFS/Arweave and referenced by content hashes.  

- **On-chain behavior**  
  - Sponsor funds entering BatchVault, RaffleVault, and Buffer Pool.  
  - Voucher redemptions, faucet drips, and raffle payouts.  
  - Expiry and recycling logic (e.g., expired allocations being returned to Buffer Pool, not random wallets).  

ProveX can publish **on-chain attestations** such as:
- “Batch #3 receipts match vendor payouts and packaging budget.”  
- “Batch #4 raffle used approved randomness and followed the rules.”  
- “All expired vouchers from Batch #5 were returned to Buffer Pool at tx XYZ.”  

The Scratchers dApp can then show:
- ✅ *ProveX Verified: Funds accounted for*  
- ✅ *ProveX Verified: Raffle fair*  
- ✅ *ProveX Verified: Ambassador invoices match payouts*  

This creates a clear line from **community donations → ambassadors → printers → end users**, with each step backed by verifiable proofs.

---

## 10. Call to Action
We are seeking:
- **Smart Contract Developers** (Solidity)  
- **Frontend Engineers** (Next.js, wallet integrations)  
- **Designers** (card art & branding)  
- **Ambassadors** (coordinate printing & distribution)  
- **Sponsors** (fund the first batch in PLS)  
- **ProveX / ProofFi Builders** (to help define attestations and integrate Scratchers as a flagship “proof-backed” dApp)  

👉 Together, we can make onboarding to PulseChain as easy as scratching a card — and with ProveX, we can prove to the world that every PLS and every card is used exactly how we say it is.
