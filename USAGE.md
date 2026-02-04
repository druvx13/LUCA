# LUCA Free License - Usage Guide

## How to Apply LUCA to Your Project

### Step 1: Add the License File

Copy the LUCA license text to a file named `COPYING` in your project root:

```bash
curl -o COPYING https://raw.githubusercontent.com/druvx13/LUCA/main/COPYING
```

Or manually create `COPYING` with this content:

```
LUCA FREE LICENSE
            (Liberty Unrestricted for Creative Autonomy)
                    Version 1.0, February 2026

 Copyright (C) [YEAR] [YOUR NAME/ORGANIZATION]

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.

  1. NO WARRANTY. THE WORK IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND.
     YOU USE IT AT YOUR OWN RISK. THE AUTHOR DISCLAIMS ALL LIABILITY FOR
     DAMAGES, LOSSES, OR ANY OTHER HARM ARISING FROM YOUR USE OF THE WORK,
     WHETHER ALLEGED AS A BREACH OF CONTRACT, TORTIOUS BEHAVIOR, OR OTHERWISE.
     THIS INCLUDES BUT IS NOT LIMITED TO DAMAGES FROM BUGS, DATA LOSS, OR
     YOUR OWN STUPIDITY.

  2. IF ANY PART OF THIS LICENSE IS FOUND UNENFORCEABLE IN YOUR JURISDICTION,
     THE REST STILL APPLIES. THE CORE RULE REMAINS: DO WHAT THE FUCK YOU WANT TO.
```

**Important**: Replace `[YEAR]` with the current year and `[YOUR NAME/ORGANIZATION]` with your information.

### Step 2: Update Your README

Add a license section to your README.md:

```markdown
## License

This project is licensed under the LUCA Free License v1.0 - see the [COPYING](COPYING) file for details.

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)
```

### Step 3: (Optional) Add Source File Headers

While not required, you can add headers to your source files:

**For code files:**

```
Copyright (C) [YEAR] [YOUR NAME]
Licensed under LUCA Free License v1.0
DO WHAT THE FUCK YOU WANT TO.
```

**Examples for different languages:**

**Python:**
```python
# Copyright (C) 2026 Your Name
# Licensed under LUCA Free License v1.0
# DO WHAT THE FUCK YOU WANT TO.
```

**JavaScript/TypeScript:**
```javascript
/*
 * Copyright (C) 2026 Your Name
 * Licensed under LUCA Free License v1.0
 * DO WHAT THE FUCK YOU WANT TO.
 */
```

**C/C++/Java:**
```c
/*
 * Copyright (C) 2026 Your Name
 * Licensed under LUCA Free License v1.0
 * DO WHAT THE FUCK YOU WANT TO.
 */
```

**Go:**
```go
// Copyright (C) 2026 Your Name
// Licensed under LUCA Free License v1.0
// DO WHAT THE FUCK YOU WANT TO.
```

**Rust:**
```rust
// Copyright (C) 2026 Your Name
// Licensed under LUCA Free License v1.0
// DO WHAT THE FUCK YOU WANT TO.
```

**Ruby:**
```ruby
# Copyright (C) 2026 Your Name
# Licensed under LUCA Free License v1.0
# DO WHAT THE FUCK YOU WANT TO.
```

### Step 4: Update Package Metadata

#### npm (package.json)
```json
{
  "name": "your-package",
  "version": "1.0.0",
  "license": "SEE LICENSE IN COPYING",
  "author": "Your Name"
}
```

#### Python (setup.py)
```python
from setuptools import setup

setup(
    name='your-package',
    version='1.0.0',
    license='LUCA Free License v1.0',
    author='Your Name',
)
```

#### Python (pyproject.toml)
```toml
[project]
name = "your-package"
version = "1.0.0"
license = {text = "LUCA Free License v1.0"}
```

#### Cargo (Cargo.toml)
```toml
[package]
name = "your-package"
version = "1.0.0"
license-file = "COPYING"
```

#### Go (go.mod)
Go doesn't have built-in license metadata, but you can add a comment:

```go
// Package yourpackage is licensed under LUCA Free License v1.0
package yourpackage
```

#### Composer (composer.json)
```json
{
    "name": "vendor/package",
    "license": "proprietary",
    "description": "Licensed under LUCA Free License v1.0"
}
```

#### Maven (pom.xml)
```xml
<licenses>
    <license>
        <name>LUCA Free License</name>
        <url>https://github.com/druvx13/LUCA</url>
        <distribution>repo</distribution>
    </license>
</licenses>
```

## Badges

### Standard Badge

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)

```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg)](https://github.com/druvx13/LUCA)
```

### Version Badge

[![LUCA License](https://img.shields.io/badge/License-LUCA%20v1.0-blue.svg)](https://github.com/druvx13/LUCA)

```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA%20v1.0-blue.svg)](https://github.com/druvx13/LUCA)
```

### Flat Style

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg?style=flat)](https://github.com/druvx13/LUCA)

```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg?style=flat)](https://github.com/druvx13/LUCA)
```

### Flat Square Style

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg?style=flat-square)](https://github.com/druvx13/LUCA)

```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg?style=flat-square)](https://github.com/druvx13/LUCA)
```

### For the Badge Style

[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg?style=for-the-badge)](https://github.com/druvx13/LUCA)

```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-blue.svg?style=for-the-badge)](https://github.com/druvx13/LUCA)
```

### Custom Colors

**Green:**
```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-green.svg)](https://github.com/druvx13/LUCA)
```

**Red:**
```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-red.svg)](https://github.com/druvx13/LUCA)
```

**Purple:**
```markdown
[![LUCA License](https://img.shields.io/badge/License-LUCA-purple.svg)](https://github.com/druvx13/LUCA)
```

## Using LUCA-Licensed Code

### Can I use LUCA code in my project?

**Yes!** You can use LUCA-licensed code in any project, commercial or non-commercial.

### Do I need to include the license?

**No**, but it's good practice. If you want to acknowledge the original authors (even though it's not required):

```markdown
## Acknowledgments

- Uses code from [Project Name] - LUCA Licensed
```

### Can I modify LUCA code?

**Yes!** Modify it however you want.

### Do I need to share my modifications?

**No.** You can keep modifications private or release them under any license.

### Can I sublicense?

**Yes.** You can distribute LUCA code under a different license if you want.

## Platform-Specific Instructions

### GitHub

1. Add `COPYING` file to repository root
2. GitHub will detect it as a license file
3. Add badges to README.md
4. Optionally add topics: `luca-license`, `permissive-license`

### GitLab

1. Add `COPYING` file
2. Add license badge to README
3. In project settings, you might need to select "Other" as license type

### Bitbucket

1. Add `COPYING` file
2. Add badge to README
3. License will be shown in repository info

### Package Registries

#### npm
```json
{
  "license": "SEE LICENSE IN COPYING"
}
```

#### PyPI
In setup.py or pyproject.toml, specify:
```python
license='LUCA Free License v1.0'
```

Upload normally with `twine`.

#### crates.io
```toml
license-file = "COPYING"
```

#### Maven Central
Include license in POM as shown above.

## Displaying License Information

### In Your Application

**Command-line:**
```bash
myapp --license
# Displays: Licensed under LUCA Free License v1.0
# DO WHAT THE FUCK YOU WANT TO.
```

**Web application (footer):**
```html
<footer>
  <p>Licensed under <a href="https://github.com/druvx13/LUCA">LUCA Free License v1.0</a></p>
</footer>
```

**About dialog:**
```
MyApp v1.0
Copyright (C) 2026 Your Name
Licensed under LUCA Free License v1.0

DO WHAT THE FUCK YOU WANT TO.
```

## Best Practices

### DO:
- ✅ Include the COPYING file in your repository
- ✅ Add a badge to your README for visibility
- ✅ Mention the license in your project description
- ✅ Keep the warranty disclaimer intact

### DON'T:
- ❌ Remove the warranty disclaimer (legal protection)
- ❌ Claim the license requires attribution (it doesn't)
- ❌ Misrepresent LUCA as a copyleft license

### OPTIONAL:
- Include copyright headers in source files
- Add acknowledgments section
- Link to the LUCA repository
- Share your LUCA-licensed projects

## Checklist

Before releasing your LUCA-licensed project:

- [ ] `COPYING` file exists in repository root
- [ ] Copyright year and name are updated in COPYING
- [ ] README mentions the license
- [ ] License badge added to README (optional)
- [ ] Package metadata updated with license info
- [ ] No false claims about license requirements

## Getting Help

- Read the [FAQ](FAQ.md)
- Check the [About page](ABOUT.md)
- Visit the [documentation website](https://druvx13.github.io/LUCA/)
- Open an issue on [GitHub](https://github.com/druvx13/LUCA)

## Example Projects

Want to see LUCA in action? Here are some examples:

```markdown
# Example Project Structure

my-project/
├── COPYING              # LUCA license
├── README.md            # With LUCA badge
├── src/
│   ├── main.py         # Optional: license header
│   └── utils.py
└── package.json        # License metadata
```

**Remember**: The beauty of LUCA is its simplicity. Don't overthink it. Just **DO WHAT THE FUCK YOU WANT TO.** 🚀

## Advanced Integration

### CI/CD Integration

#### GitHub Actions

Add license validation to your workflow:

```yaml
name: License Check
on: [push, pull_request]

jobs:
  license:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Check LUCA License
        run: |
          if [ ! -f COPYING ]; then
            echo "COPYING file not found"
            exit 1
          fi
          if ! grep -q "LUCA FREE LICENSE" COPYING; then
            echo "LUCA license text not found"
            exit 1
          fi
```

#### GitLab CI

```yaml
license_check:
  stage: test
  script:
    - test -f COPYING
    - grep "LUCA FREE LICENSE" COPYING
```

#### Jenkins

```groovy
stage('License Check') {
    steps {
        sh 'test -f COPYING'
        sh 'grep "LUCA FREE LICENSE" COPYING'
    }
}
```

### IDE Integration

#### VS Code

Create `.vscode/settings.json`:

```json
{
  "files.associations": {
    "COPYING": "plaintext"
  },
  "licenser.license": "Custom",
  "licenser.customHeader": [
    "Copyright (C) 2026 Your Name",
    "Licensed under LUCA Free License v1.0",
    "DO WHAT THE FUCK YOU WANT TO."
  ]
}
```

#### IntelliJ IDEA

1. Go to Settings → Editor → Copyright → Copyright Profiles
2. Add new profile with LUCA text
3. Set as default

### Docker Integration

**Dockerfile:**
```dockerfile
FROM alpine:latest

# Include license (optional but good practice)
COPY COPYING /usr/share/licenses/yourapp/COPYING

# Your application
COPY app /app
WORKDIR /app
CMD ["./yourapp"]
```

**docker-compose.yml:**
```yaml
version: '3'
services:
  app:
    image: yourapp:latest
    labels:
      - "org.opencontainers.image.licenses=LUCA-1.0"
      - "org.opencontainers.image.license-url=https://github.com/druvx13/LUCA"
```

### Kubernetes Integration

**deployment.yaml:**
```yaml
apiVersion: v1
kind: ConfigMap
metadata:
  name: license-configmap
data:
  COPYING: |
    LUCA FREE LICENSE
    ...your license text...
---
apiVersion: apps/v1
kind: Deployment
metadata:
  name: yourapp
  labels:
    license: LUCA-1.0
spec:
  template:
    spec:
      containers:
      - name: app
        volumeMounts:
        - name: license
          mountPath: /licenses
      volumes:
      - name: license
        configMap:
          name: license-configmap
```

## Platform-Specific Advanced Usage

### Mobile Apps

#### iOS (CocoaPods)

**Podspec:**
```ruby
Pod::Spec.new do |s|
  s.name         = "YourLibrary"
  s.version      = "1.0.0"
  s.license      = { :type => 'Custom', :file => 'COPYING' }
  s.author       = { "Your Name" => "email@example.com" }
end
```

#### Android (Gradle)

**build.gradle:**
```gradle
android {
    defaultConfig {
        manifestPlaceholders = [license: "LUCA-1.0"]
    }
}
```

**AndroidManifest.xml:**
```xml
<meta-data
    android:name="license"
    android:value="${license}" />
```

### Web Applications

#### Express.js (Node)

```javascript
const express = require('express');
const fs = require('fs');
const app = express();

// Serve license
app.get('/license', (req, res) => {
  const license = fs.readFileSync('COPYING', 'utf8');
  res.type('text/plain').send(license);
});

// Add to API responses
app.use((req, res, next) => {
  res.setHeader('X-License', 'LUCA-1.0');
  next();
});
```

#### Django (Python)

```python
# settings.py
LICENSE = 'LUCA Free License v1.0'

# views.py
from django.http import HttpResponse
from django.conf import settings

def license_view(request):
    with open('COPYING', 'r') as f:
        return HttpResponse(f.read(), content_type='text/plain')

# Add to context processor
def license_processor(request):
    return {'license': settings.LICENSE}
```

#### Flask (Python)

```python
from flask import Flask, send_file

app = Flask(__name__)

@app.route('/license')
def license():
    return send_file('COPYING', mimetype='text/plain')

@app.after_request
def add_license_header(response):
    response.headers['X-License'] = 'LUCA-1.0'
    return response
```

### Desktop Applications

#### Electron

**package.json:**
```json
{
  "name": "your-app",
  "license": "SEE LICENSE IN COPYING",
  "build": {
    "extraResources": [
      "COPYING"
    ]
  }
}
```

**Show license in app:**
```javascript
const { app, BrowserWindow, Menu } = require('electron');
const fs = require('fs');
const path = require('path');

function showLicense() {
  const licensePath = path.join(app.getAppPath(), 'COPYING');
  const license = fs.readFileSync(licensePath, 'utf8');
  
  // Create window to display license
  const win = new BrowserWindow({
    width: 600,
    height: 400,
    title: 'License'
  });
  
  win.loadURL(`data:text/plain;charset=utf-8,${encodeURIComponent(license)}`);
}

// Add to menu
const template = [
  {
    label: 'Help',
    submenu: [
      {
        label: 'License',
        click: showLicense
      }
    ]
  }
];

Menu.setApplicationMenu(Menu.buildFromTemplate(template));
```

## Troubleshooting

### Common Issues

#### Issue: Package registry rejects LUCA

**Solution:** Use "SEE LICENSE IN COPYING" or specify as custom license. Some registries require manual review.

#### Issue: License scanner doesn't recognize LUCA

**Solution:** Add LUCA to your scanner's whitelist or configure as equivalent to MIT without attribution requirement.

#### Issue: Corporate legal team blocks LUCA

**Solution:** 
1. Show them the warranty disclaimer
2. Compare with MIT (LUCA is similar but more permissive)
3. Explain the severability clause
4. If still blocked, use MIT or Apache 2.0

#### Issue: GitHub doesn't show license badge

**Solution:** GitHub may not auto-detect custom licenses. Add a badge manually using shields.io.

#### Issue: Contributors confused about licensing

**Solution:** Add a CONTRIBUTING.md explaining that contributions are LUCA-licensed.

### Migration Guides

#### From MIT to LUCA

1. Replace LICENSE/MIT with COPYING
2. Update package.json/setup.py/etc.
3. Update README badges
4. Remove attribution requirements from docs
5. Announce the change

#### From WTFPL to LUCA

1. Add COPYING file (LUCA text)
2. Keep existing WTFPL references as historical note
3. Update documentation
4. LUCA provides better legal protection

#### From Apache 2.0 to LUCA

1. Replace LICENSE with COPYING
2. Remove NOTICE file (not needed)
3. Update all references
4. Note: Loses explicit patent grant details

---

**Remember**: The beauty of LUCA is its simplicity. Don't overthink it. Just **DO WHAT THE FUCK YOU WANT TO.** 🚀
