# Librarian Negotiations v1.0.3-mc26.1.2

## Rebrand

- Renamed the mod from **Librarian's Bargain** to **Librarian Negotiations** to better reflect the negotiation-focused gameplay.
- Changed the mod ID from `njw_librarians_bargain` to `njw_librarian_negotiations`.
- Updated the item/data resource namespace and mod metadata for the new ID.

## Negotiations

- Bargaining and rerolling proposals no longer consume Diamonds.
- Accepting a final proposal costs **7 Diamonds** and closes the negotiation screen.
- Negotiation attempts can be rejected at **5%**, **15%**, or **25%** depending on active locks.
- Rejected attempts keep the current proposal list unchanged.
- Three rejected attempts forcibly end the negotiation.
- Rejection feedback uses a short, high-pitched anvil sound.
- Proposal acceptance tooltips follow the mouse directly.

## Mysterious Contract

- The contract is consumed when a valid negotiation begins.
- The contract has a maximum stack size of 1.
- The recipe is now shapeless: **1 Book and Quill + 1 Emerald + 1 Blaze Rod**.
- The recipe is unlocked after trading with a villager.

## Compatibility

- Minecraft **26.1.2**
- NeoForge **26.1.2.97+**
- Java **25**

> Note: because the mod ID changed, existing Mysterious Contract item stacks from older versions use the previous registry ID and are not migrated automatically.
