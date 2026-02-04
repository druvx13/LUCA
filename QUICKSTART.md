# LUCA Quick Start Guide

Get started with the LUCA Free License in under 5 minutes.

## What is LUCA?

**LUCA** = Liberty Unrestricted for Creative Autonomy

A free software license that gives you **maximum freedom**:
- ✅ Use anywhere (commercial, private, etc.)
- ✅ Modify however you want
- ✅ Distribute freely
- ❌ No attribution required
- ❌ No copyleft restrictions

**Core principle:** **DO WHAT THE FUCK YOU WANT TO.**

## For Project Owners

### 3-Step Setup

**Step 1:** Download the license
```bash
curl -o COPYING https://raw.githubusercontent.com/druvx13/LUCA/main/COPYING
```

**Step 2:** Update copyright (edit COPYING file)
```
Copyright (C) 2026 Your Name
```

**Step 3:** Add badge to README (optional)
```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)
```

**Done!** Your project is now LUCA-licensed.

### Example README Section

```markdown
## License

This project is licensed under the LUCA Free License v1.0.

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)

**DO WHAT THE FUCK YOU WANT TO.**
```

## For Users

### Can I use LUCA-licensed code?

**Yes!** You can:
- ✅ Use it commercially
- ✅ Modify it
- ✅ Distribute it
- ✅ Keep modifications private
- ✅ Relicense under different terms
- ✅ Use without attribution

### Do I need to do anything?

**No!** LUCA requires nothing from you. Just use the code.

## Common Scenarios

### Scenario 1: Starting a New Project

```bash
# Create your project
mkdir my-awesome-project
cd my-awesome-project

# Initialize git
git init

# Add LUCA license
curl -o COPYING https://raw.githubusercontent.com/druvx13/LUCA/main/COPYING

# Edit copyright
sed -i 's/2026 Anonymous/2026 Your Name/' COPYING

# Create README with badge
cat > README.md << 'EOF'
# My Awesome Project

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)

## License

Licensed under LUCA Free License v1.0 - DO WHAT THE FUCK YOU WANT TO.
EOF

# Start coding!
```

### Scenario 2: Adding to Existing Project

```bash
# Navigate to your project
cd my-existing-project

# Download license
curl -o COPYING https://raw.githubusercontent.com/druvx13/LUCA/main/COPYING

# Update copyright year and name in COPYING file
# Then add to git
git add COPYING
git commit -m "Add LUCA license"

# Update README (add badge and license section)
```

### Scenario 3: Using LUCA Code in Your Project

```bash
# That's it! No steps needed!
# Just use the code however you want.
# Attribution is optional but appreciated.
```

### Scenario 4: Publishing to Package Registry

**npm:**
```bash
# In package.json
{
  "license": "SEE LICENSE IN COPYING"
}

npm publish
```

**PyPI:**
```bash
# In setup.py or pyproject.toml
license = "LUCA Free License v1.0"

python -m build
twine upload dist/*
```

**crates.io:**
```bash
# In Cargo.toml
[package]
license-file = "COPYING"

cargo publish
```

## Quick Troubleshooting

### Problem: Don't know what license to choose?

**Solution:** If you want maximum freedom and simplicity → LUCA  
If you need attribution → MIT  
If you want copyleft → GPL

### Problem: Company legal team is concerned

**Solution:** Show them:
1. LUCA has proper warranty disclaimers
2. It's similar to MIT but more permissive
3. See the full [FAQ](FAQ.md)

### Problem: Package registry doesn't recognize LUCA

**Solution:** Use "SEE LICENSE IN COPYING" or mark as custom license. Most registries accept this.

## Quick Reference Card

```
┌─────────────────────────────────────────┐
│         LUCA LICENSE CHEAT SHEET        │
├─────────────────────────────────────────┤
│                                         │
│ ✅ CAN DO:                              │
│   • Use commercially                    │
│   • Modify freely                       │
│   • Distribute                          │
│   • Keep private                        │
│   • Sublicense                          │
│   • No attribution needed               │
│                                         │
│ ❌ CANNOT EXPECT:                       │
│   • Warranty                            │
│   • Liability coverage                  │
│                                         │
│ 📋 MUST HAVE:                           │
│   • COPYING file in project root        │
│   • Warranty disclaimer intact          │
│                                         │
│ 💡 OPTIONAL:                            │
│   • Attribution                         │
│   • License badge                       │
│   • Source file headers                 │
│                                         │
└─────────────────────────────────────────┘
```

## Learn More

- 📖 **Full Documentation:** [README.md](README.md)
- ❓ **Questions?** [FAQ.md](FAQ.md)
- 🚀 **Detailed Guide:** [USAGE.md](USAGE.md)
- 🌐 **Website:** https://druvx13.github.io/LUCA/

## Support

- 🐛 [Report Issues](https://github.com/druvx13/LUCA/issues)
- 💬 [Discussions](https://github.com/druvx13/LUCA/discussions)
- 📧 Contact: See repository

---

**Licensed under LUCA v1.0 - DO WHAT THE FUCK YOU WANT TO.**
