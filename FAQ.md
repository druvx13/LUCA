# LUCA Free License - FAQ

## General Questions

### What is LUCA?

LUCA (Liberty Unrestricted for Creative Autonomy) is a permissive free software license that gives users maximum freedom. The core principle is simple: **DO WHAT THE FUCK YOU WANT TO.**

### Is LUCA a real license?

Yes! While informal in tone, LUCA is a legally constructed license with proper warranty disclaimers and severability clauses.

### Is LUCA approved by OSI?

LUCA is newly created (February 2026) and has not yet been submitted to the Open Source Initiative for approval. However, it meets the spirit of the Open Source Definition by granting all essential freedoms.

### How do you pronounce LUCA?

"LOO-kah" (like the name Lucas without the 's')

## Legal Questions

### Can I use LUCA for commercial projects?

**Absolutely yes.** Commercial use is fully permitted with zero restrictions or obligations.

### Do I need to include attribution?

**No.** While attribution is always appreciated and is good community practice, LUCA doesn't require it. You can use LUCA-licensed code without any attribution.

### Can I modify LUCA-licensed code?

**Yes.** You can modify the code in any way you want. You can also distribute your modifications without any restrictions.

### Do I need to share my modifications?

**No.** Unlike copyleft licenses (GPL), LUCA doesn't require you to share your modifications or release them under the same license.

### Can I relicense LUCA-licensed code under a different license?

**Yes.** You can take LUCA-licensed code and release it (original or modified) under any license you choose, including proprietary licenses.

### What about patents?

LUCA includes an implicit patent grant. Contributors cannot later sue you for patent infringement for using the code they released under LUCA.

### Is there any warranty?

**No.** LUCA explicitly disclaims all warranties. The software is provided "as is" and you use it at your own risk.

### Who is liable if something goes wrong?

**No one.** The license clearly states that the author disclaims all liability for damages, losses, or harm arising from use of the software.

### What if part of LUCA is found unenforceable?

The severability clause ensures that if any part is unenforceable in your jurisdiction, the rest of the license still applies. The core principle remains: do what you want.

## Usage Questions

### How do I apply LUCA to my project?

1. Copy the `COPYING` file to your project root
2. Add a badge to your README (optional)
3. Optionally add license headers to your source files

See [USAGE.md](USAGE.md) for detailed instructions.

### Can I use LUCA for documentation, not just code?

**Yes.** While designed for software, LUCA can be used for documentation, artwork, or any other creative work.

### Should I include the license in every source file?

It's not required, but you can if you want. A simple header like this works:

```
Copyright (C) [YEAR] [YOUR NAME]
Licensed under LUCA Free License v1.0
```

### Can I use LUCA with other licenses in the same project?

Yes, but be careful. If you're combining code:
- LUCA is compatible with other permissive licenses (MIT, BSD, Apache)
- Be cautious with GPL (it has copyleft requirements)
- Always follow the most restrictive license when combining code

### What if I want to require attribution?

Then LUCA isn't the right license for you. Consider MIT or Apache 2.0 instead.

## Comparison Questions

### How is LUCA different from MIT?

**MIT** requires attribution in all distributions. **LUCA** doesn't require anything except "do what you want."

### How is LUCA different from GPL?

**GPL** is copyleft - it requires derivatives to also be GPL. **LUCA** has no such requirement. You can make your derivatives proprietary.

### How is LUCA different from WTFPL?

**LUCA** includes more explicit legal protections (warranty disclaimers, severability) while maintaining WTFPL's spirit of maximum freedom.

### How is LUCA different from Unlicense/Public Domain?

**Public Domain** means no copyright at all. **LUCA** maintains copyright but grants maximum permissions. In some jurisdictions, public domain dedications aren't legally valid, but licenses are.

### Which is more permissive: LUCA or MIT?

**LUCA** is more permissive because it doesn't require attribution.

### Should I use LUCA or MIT?

- Choose **LUCA** if you want maximum freedom and don't care about attribution
- Choose **MIT** if you want attribution or need a well-established license

## Technical Questions

### Can I use LUCA for my npm package?

**Yes.** In your `package.json`, use:

```json
{
  "license": "SEE LICENSE IN COPYING"
}
```

Or create a custom identifier (npm allows this).

### Can I use LUCA on GitHub?

**Yes.** GitHub will recognize the COPYING file, though it may not auto-detect it as a known license.

### Can I use LUCA for my Python package?

**Yes.** In your setup.py or pyproject.toml:

```python
license = "LUCA Free License v1.0"
```

### Will package repositories accept LUCA?

Most package repositories accept custom licenses as long as they're clearly documented. Some might require you to specify "Other" or "Custom" as the license type.

### Can I mix LUCA code with GPL code?

Technically possible but complicated. GPL requires derivatives to be GPL-licensed, which conflicts with LUCA's freedom. If you must combine them, follow GPL's requirements for the combined work.

### Does LUCA work with Docker/containers?

Yes! LUCA-licensed code works perfectly in containers. Just include the COPYING file if you want (not required).

### How do I handle LUCA in license compliance tools?

Configure your tools to recognize LUCA as a permissive license similar to MIT but without attribution requirements. Whitelist it in your compliance policies.

### Can I use LUCA for firmware?

Yes! LUCA works for any software, including firmware, embedded systems, and hardware control code.

### What about SaaS applications?

LUCA has no "SaaS loophole" like AGPL. You can use LUCA code in SaaS without any disclosure requirements.

## Philosophical Questions

### Why create another license?

Because sometimes existing licenses aren't quite right. We wanted something that's:
- As permissive as WTFPL
- More legally sound than WTFPL
- Simpler than MIT
- More freedom than MIT (no attribution requirement)

### Isn't this just WTFPL with extra steps?

Sort of! LUCA is inspired by WTFPL but includes important legal protections and clearer structure while maintaining the same spirit.

### Why the profanity?

The phrase "DO WHAT THE FUCK YOU WANT TO" is clear, memorable, and has precedent in licenses like WTFPL. It perfectly captures the license's spirit. If this bothers you, there are many other excellent licenses available.

### Isn't giving away all rights dangerous?

Not really. You're giving away rights to use the *code*, not rights to your *name* or *trademark*. And the warranty disclaimer protects you from liability.

### What if someone uses my LUCA code for evil?

They can. That's the nature of true freedom. If you want to restrict use, you need a different license with ethical clauses (which may not be enforceable anyway).

### Can corporations really be trusted with this much freedom?

LUCA is based on trust and freedom. If you're concerned about corporate exploitation, consider copyleft licenses like GPL. LUCA is for those who prioritize freedom over control.

### What about trademark protection?

LUCA doesn't address trademarks. Your project name and branding remain yours. The license only covers the code itself.

### Can I revoke LUCA license after releasing?

No. Once you release code under LUCA, recipients have permanent rights to that version. You can change the license for future versions, but past versions remain LUCA-licensed.

### What happens if LUCA becomes incompatible with new laws?

The severability clause ensures that if part becomes unenforceable, the rest remains valid. The core freedom principle would persist.

## Community Questions

### Can I contribute to LUCA documentation?

**Yes!** The documentation is also LUCA-licensed. Contribute however you want.

### Can I translate LUCA?

**Yes!** Translations are welcome. Just note that the English version is the official legal text.

### Can I create a derivative license?

**Yes!** The license itself is LUCA-licensed. We just ask (but don't require) that you change the name if you significantly modify it.

### Where can I get help?

- Open an issue on the [GitHub repository](https://github.com/druvx13/LUCA)
- Check the [documentation website](https://druvx13.github.io/LUCA/)
- Ask in the community

### Can I use the LUCA badges?

**Yes!** All badges and graphics are LUCA-licensed. Use them freely.

## Still Have Questions?

If your question isn't answered here:

1. Check the [full license text](COPYING)
2. Read the [About page](ABOUT.md)
3. Review the [Usage Guide](USAGE.md)
4. Open an issue on GitHub

And remember: when in doubt, the license says **DO WHAT THE FUCK YOU WANT TO.** 😉

## Advanced Questions

### Can I use LUCA in a monorepo with multiple licenses?

**Yes.** Different parts of a monorepo can have different licenses. Just clearly document which license applies to which part.

### How does LUCA handle derivative works?

LUCA doesn't restrict derivative works at all. You can create derivatives and license them however you want, including proprietary licenses.

### What about contribution licensing?

If someone contributes to your LUCA project, their contribution is under LUCA by default (unless specified otherwise). Consider adding a note about this in CONTRIBUTING.md.

### Can I dual-license with LUCA and another license?

**Yes.** You can offer your code under LUCA and another license (e.g., commercial license for enterprise support). This is common for open-core models.

### Does LUCA protect against patent trolls?

LUCA includes an implicit patent grant, meaning contributors can't sue users for patent infringement. However, it doesn't provide the same extensive patent protections as Apache 2.0.

### Can government agencies use LUCA?

**Yes.** Government agencies can use LUCA-licensed code. Some might prefer more established licenses for procurement reasons, but LUCA is legally valid.

### How does LUCA handle license violations?

Since LUCA has no requirements to violate, there are no license violations. However, the warranty disclaimer still protects the author.

### Can I use LUCA for closed-source projects?

LUCA is for releasing *open* code. If you want to release closed-source software, you don't need LUCA - you already have full control via copyright.

### What if I want to add LUCA to an existing project?

You can relicense if you own all the code or have permission from all contributors. Otherwise, you can only apply LUCA to new code you write.

### How do I cite LUCA in academic papers?

You can cite LUCA as:
```
LUCA Free License (Version 1.0). (2026). Retrieved from https://github.com/druvx13/LUCA
```

## Troubleshooting

### My company's legal team is concerned about LUCA

Show them:
1. The full license text (COPYING)
2. Comparison with other permissive licenses
3. The warranty disclaimer and severability clause
4. This FAQ's legal section

If they remain concerned, consider MIT or Apache 2.0 instead.

### GitHub doesn't recognize my LUCA license

GitHub may not auto-detect LUCA as it's a custom license. This is normal and doesn't affect the legal validity. The COPYING file is still recognized.

### My dependency scanner flags LUCA

Configure your scanner to whitelist LUCA. It's as permissive as MIT but without attribution requirements, making it safe for commercial use.

### Package registry rejects my LUCA package

Use "SEE LICENSE IN COPYING" or similar for the license field. Some registries might require manual approval for custom licenses.

### I accidentally used LUCA code without knowing

**No problem!** LUCA doesn't require anything from you. Just use the code and don't worry about it.

---

*This FAQ is licensed under LUCA v1.0. Feel free to adapt it for your own projects.*
