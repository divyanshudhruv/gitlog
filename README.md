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
🎉 init(project): initial commit
```
<br>

**`1.`** **Features and enhancement**
```markdown
✨ feat(): new feature
```
```markdown
⚡ perf(): performance improvements
```
```markdown
🎨 design(): ui/ux design improvements
```
```markdown
📈 analytics(): analytics or tracking code
```
```markdown
🔌 integration(): external integrations
```

<br>

**`2.`** **Bug fixes**
```markdown
🐛 fix(): bug fix
```
```markdown
🔍 debug(): debugging changes
```
```markdown
👨‍🔧 patch(): minor fix or patch
```

<br>

**`3.`** **Documentation**
```markdown
📚 docs(): documentation changes
```
```markdown
📝 update(): minor updates
```
```markdown
📖 guide(): update or add a guide
```

<Br>

**`4.`** **Code styling and refactoring**
```markdown
💄 style(): code formatting
```
```markdown
♻️ refactor(): code refactoring
```
```markdown
🧹 cleanup(): clean-up or refactor of unused code
```
```markdown
🛠️ fix(): code improvements
```
```markdown
🔥 remove(): removing files or code
```

<br>

**`5.`** **Testing and maintenance**
```markdown
✔️ test(passed): adding/modifying/result tests
```
```markdown
❌ test(failed): adding/modifying/result tests
```
```markdown
🔧 chore(): maintenance tasks
```
```markdown
🔨 build(): changes to the build process
```
```markdown
🚧 wip(): work in progress
```
```markdown
📊 metrics(): metrics and monitoring
```

<br>

**`6.`**Non-feature Changes****

```
🚚 non-feature(): non-feature change (json)
```

<Br>

**`7.`** **Security and reverting changes**
```markdown
🔒 security(): security improvements
```
```markdown
📌 revert(): reverting previous changes
```
```markdown
🛡️ protect(): security patches or fixes
```
```markdown
🔌 api(): api-related changes
```

<br>

**`8.`** **Deployments and builds**
```markdown
🚀 deploy(): deploy-related changes
```
```markdown
📦 build(): changes to build configuration
```
```markdown
🧪 ci(): continuous Integration changes
```
```markdown
🔨 setup(): setup or config changes
```
```
🧰 deps(): adjust dependencies (upgrade/downgrade)
```

<Br>

**`9.`** **Database and infrastructure**
```markdown
🗃️ db(): database changes
```
```markdown
👷 infra(): infrastructure improvements
```
```markdown
📡 network(): network configurations or updates
```

<br>

**`10.`** **Others**

```markdown
📤 release(): new releases or version bumps
```
```markdown
📜 dumpversion(): dumping version info or changelog
```
```markdown
🔄 ref(): reference updates or reorganization
```
```markdown
💬 discussion(): ongoing discussions or issue resolutions
```
```markdown
⚙️ config(): configuration changes
```
```markdown
🔧 tweak(): minor adjustments or tweaks
```
```markdown
🚨 alert(): important notices or warnings
```

<br>

**`11.`** **Please**
```markdown
🙏 pls(): request or polite suggestion
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
