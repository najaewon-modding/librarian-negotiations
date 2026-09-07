# Librarian Negotiations

**Librarian Negotiations** is a Minecraft mod for negotiating librarian enchanted-book trades without repeatedly breaking and replacing lecterns.

Use a **Mysterious Contract** on an eligible librarian to open a negotiation, compare several proposals, lock parts of an offer, reroll proposals, and decide whether to accept a final deal.

## Features

* Use a **Mysterious Contract** on an untraded librarian that currently offers an enchanted book.
* The contract is consumed when a valid negotiation is opened and has a maximum stack size of 1.
* The current librarian trade appears as the first proposal when negotiation begins.
* Generate and reroll proposals without spending Diamonds.
* Lock the enchantment when negotiating again.
* Lock the level after locking the enchantment.
* Locks increase the chance that the librarian rejects a negotiation attempt:
  * **5%** with no locks.
  * **15%** with one lock.
  * **25%** with two locks.
* A rejected attempt leaves the current proposal list unchanged.
* After **3 rejected attempts**, the negotiation screen is forcibly closed.
* Rejections use a short, high-pitched anvil sound for clear feedback.
* Accepting a final proposal costs **7 Diamonds**.
* The acceptance tooltip follows the mouse directly and shows the 7-Diamond cost.
* After a proposal is accepted, the negotiation screen closes automatically.
* Closing the screen without accepting a proposal keeps the librarian's current trade unchanged.

## Mysterious Contract

The recipe is shapeless:

* 1 Book and Quill
* 1 Emerald
* 1 Blaze Rod

The recipe is unlocked after trading with a villager.

## Negotiation Model

> **Mysterious Contract = Access to negotiation**  
> **Locks = Higher rejection risk**  
> **7 Diamonds = Final acceptance cost**

Rerolling itself is free. The player pays through risk while negotiating and spends Diamonds only when committing to a final offer.

## Compatibility

* Minecraft **26.1.2**
* NeoForge **26.1.2.97+**
* Java **25**

## Technical

* Mod ID: `njw_librarian_negotiations`

### Updating from Librarian's Bargain

The mod ID changed from `njw_librarians_bargain` to `njw_librarian_negotiations`. Existing Mysterious Contract item stacks from older versions use the previous registry ID and are not migrated automatically.

## License

MIT
