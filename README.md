# ⚡ Gitlog
🔦 A **`list`** of common **`git`** commit messages for **`clear`** and **`consistent`** version control. Just **`copy`**, **`paste`** and **`customize`**. 

> **`💡 Inspiration`**[^1].


<br>

> [!IMPORTANT]
> 🍰 Before getting started, please **`familiarize`** yourself with the proper commit message **`format`**, including the use of **`emojis`** for different commit types.

> [!CAUTION]
> 🙏 Kindly do not use the default **`Update file`** message.

<br>

## Message format
🪪 A **`standardized`** structure used during **`commits`** to maintain **`clarity`** and **`consistency`** in project history.
<br>

```markdown
<emoji> <type>(<scope>): <subject>

<body>

<footer>
```

<br>

## Merge format
🥏 A format used during **`merges`** to clearly document **`merge actions`** in the project **history**.
```markdown
<emoji> <type>(<scope>): <subject>

- <points>
- <points>

Contributor: <user>
Co-contributor: <user>
Closes #<issue>
```

<br>

## Commit messages: 
🌃 Common types of **`commit messages`** with their corresponding **`emojis`**:

<br>


**`0.`** **Initialization**

```markdown
🎉 init(project): Initial commit
```
<br>

**`1.`** **Features and enhancement**
```markdown
✨ feat(): New feature
```
```markdown
⚡ perf(): Performance improvements
```
```markdown
🎨 design(): UI/UX design improvements
```
```markdown
📈 analytics(): Analytics or tracking code
```
```markdown
🔌 integration(): External integrations
```

<br>

**`2.`** **Bug fixes**
```markdown
🐛 fix(): Bug fix
```
```markdown
🔍 debug(): Debugging changes
```
```markdown
👨‍🔧 patch(): Minor fix or patch
```

<br>

**`3.`** **Documentation**
```markdown
📚 docs(): Documentation changes
```
```markdown
📝 update(): Minor updates
```
```markdown
📖 guide(): Update or add a guide
```

<Br>

**`4.`** **Code styling and refactoring**
```markdown
💄 style(): Code formatting
```
```markdown
♻️ refactor(): Code refactoring
```
```markdown
🧹 cleanup(): Clean-up or refactor of unused code
```
```markdown
🛠️ fix(): Code improvements
```
```markdown
🔥 remove(): Removing files or code
```

<br>

**`5.`** **Testing and maintenance**
```markdown
✔️ test(passed): Adding/modifying/result tests
```
```markdown
❌ test(failed): Adding/modifying/result tests
```
```markdown
🔧 chore(): Maintenance tasks
```
```markdown
🔨 build(): Changes to the build process
```
```markdown
🚧 wip(): Work in progress
```
```markdown
📊 metrics(): Metrics and monitoring
```

<Br>

**`6.`** **Security and reverting changes**
```markdown
🔒 security(): Security improvements
```
```markdown
📌 revert(): Reverting previous changes
```
```markdown
🛡️ protect(): Security patches or fixes
```
```markdown
🔌 api(): API-related changes
```

<br>

**`7.`** **Deployments and builds**
```markdown
🚀 deploy(): Deploy-related changes
```
```markdown
📦 build(): Changes to build configuration
```
```markdown
🧪 ci(): Continuous Integration changes
```
```markdown
🔨 setup(): Setup or config changes
```

<Br>

**`8.`** **Database and infrastructure**
```markdown
🗃️ db(): Database changes
```
```markdown
👷 infra(): Infrastructure improvements
```
```markdown
📡 network(): Network configurations or updates
```

<br>

**`9.`** **Others**

```markdown
📤 release(): New releases or version bumps
```
```markdown
📜 dumpversion(): Dumping version info or changelog
```
```markdown
🔄 ref(): Reference updates or reorganization
```
```markdown
💬 discussion(): Ongoing discussions or issue resolutions
```
```markdown
⚙️ config(): Configuration changes
```
```markdown
🔧 tweak(): Minor adjustments or tweaks
```
```markdown
🚨 alert(): Important notices or warnings
```

<br>

**`10.`** **Please**
```markdown
🙏 pls(): Request or polite suggestion
```

<br>

## Commit message scopes:
💡 Following **`scopes`** are commonly used in **`commit messages`** to indicate specific areas of the **`project`** affected by the **`changes`**:

<Br> 

- `auth`
- `api`
- `ui`
- `database`
- `components`
- `config`
- `tests`
- `security`
- `build`
- `server`
- `styles`
- `checkout`
- `payments`
- `notifications`
- `user`
- `css`
- `layout`
- `frontend`
- `backend`
- `forms`
- `router`
- `passed`
- `failed`

<Br>

## Contributing

⛓️‍💥 Feel **`free`** to submit **`pull requests`** to add more **`commit types`** or **`scope types`** to this list.

<br>

[^1]: [commit-messages](https://github.com/mostypc123/commit-messages)
