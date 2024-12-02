<style>
        :root {
            --color-bg: #353543;
            --color-surface: #333355;
            --color-elevated: #3d3d4d;
            --color-text: #ffffff;
            --color-text-secondary: #e2e8f0;
            --color-border: rgba(255, 255, 255, 0.1);
            --radius-base: 8px;
            --radius-lg: 16px;
            --shadow-sm: 0 2px 4px rgba(0,0,0,0.2);
            --shadow-md: 0 4px 8px rgba(0,0,0,0.3);
            --transition: 0.2s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background: var(--color-bg);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--color-text);
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            background: linear-gradient(135deg, #333355 0%, #353543 100%);
            color: white;
            padding: 3rem 2rem;
            border-radius: var(--radius-lg);
            margin-bottom: 3rem;
            text-align: center;
            box-shadow: var(--shadow-md);
        }

        .header h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            background: linear-gradient(to right, #fff, #e2e8f0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .type-header {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.75rem 1.5rem;
            border-radius: var(--radius-base);
            margin: 2rem 0 1rem;
            color: white;
            font-weight: 600;
            font-size: 1.25rem;
            transition: var(--transition);
        }

        .type-header:hover {
            transform: translateX(4px);
            filter: brightness(1.1);
        }

        .scope-tag {
            display: inline-block;
            padding: 0.25rem 0.75rem;
            background: var(--color-surface);
            border: 1px solid var(--color-border);
            border-radius: var(--radius-base);
            font-size: 0.875rem;
            font-weight: 500;
            color: var(--color-text);
            margin: 0.5rem 0;
            transition: var(--transition);
        }

        .scope-tag:hover {
            transform: translateY(-1px);
            box-shadow: var(--shadow-md);
            border-color: var(--color-text-secondary);
        }

        .commit-list {
            list-style: none;
            margin: 1rem 0;
        }

        .commit-item {
            background: var(--color-surface);
            border: 1px solid var(--color-border);
            border-radius: var(--radius-base);
            padding: 1rem;
            margin-bottom: 1rem;
            transition: var(--transition);
        }

        .commit-item:hover {
            transform: translateY(-2px);
            box-shadow: var(--shadow-md);
            border-color: var(--color-text-secondary);
            background: var(--color-elevated);
        }

        .commit-title {
            font-size: 1rem;
            font-weight: 600;
            color: var(--color-text);
        }

        .commit-meta {
            font-size: 0.875rem;
            color: var(--color-text-secondary);
            margin-top: 0.5rem;
        }

        .commit-body {
            background: var(--color-bg);
            border: 1px solid var(--color-border);
            border-radius: var(--radius-base);
            padding: 1rem;
            margin: 0.5rem 0;
            font-family: monospace;
            white-space: pre-wrap;
            font-size: 0.875rem;
        }

        details {
            margin: 1rem 0;
        }

        summary {
            cursor: pointer;
            margin-bottom: 1rem;
        }

        summary::-webkit-details-marker {
            display: none;
        }
    
.type-feat { background: #2563eb; }
.type-fix { background: #dc2626; }
.type-docs { background: #7c3aed; }
.type-style { background: #db2777; }
.type-refactor { background: #2dd4bf; }
.type-perf { background: #f59e0b; }
.type-test { background: #10b981; }
.type-chore { background: #6b7280; }</style>
<div class='container'>
<header class='header'>
<h1>🚀 Release v2024.11.29</h1>
<p>Released on 29 November 2024</p>
</header>
<div class="type-header type-feat">✨ Feats</div>
<details open>
<summary><span class='scope-tag'>GitHub</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Auto generate changelogs</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Auto generate changelogs</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Change the output format provided by claude ai</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Change the output format</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Allow the py script to fetch commits from the repo</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Export commit message as log.md file</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Integrate github action to generate commit text docs 4</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Integrate github action to generate commit text docs 3</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Integrate github action to generate commit text docs 2</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Integrate github action to generate commit text docs</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Generate all required scripts for each repo</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Hide the git pull output</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Add feature to auto update the commit message checker</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Generate .github and hooks for each repository</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Make the generation of the commit-msg checker easy and just by one command</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Remove pull request from github action 3</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Remove pull request from github action 2</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Remove pull request from github action</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Add pull request github action</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Move the check of the type as first</div>
</li>
</ul>
</details>
<details open>
<summary><span class='scope-tag'>Authentication</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Move the check of the type as first</div>
</li>
</ul>
</details>
<details open>
<summary><span class='scope-tag'>API</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Refactor the code and add more template types</div>
</li>
</ul>
</details>
<details open>
<summary><span class='scope-tag'>Tools</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Add setup bash file</div>
</li>
</ul>
</details>
<details open>
<summary><span class='scope-tag'>Github</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Add Github commit validation template</div>
</li>
</ul>
</details>
<div class="type-header type-fix">🐛 Fixs</div>
<details open>
<summary><span class='scope-tag'>GitHub</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Create release with change logs with specific version tag</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Create release with change logs</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Auto generate change logs4</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Auto generate change logs3</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Auto generate change logs2</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Auto generate change logs</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Create release action</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Change release type</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Add change log ci action</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Update the output of the commit</div>
</li>
<li class='commit-item'>
<div class='commit-title'>Change the output format provided by claude ai</div>
</li>
</ul>
</details>
<div class="type-header type-style">💎 Styles</div>
<details open>
<summary><span class='scope-tag'>GitHub</span></summary>
<ul class='commit-list'>
<li class='commit-item'>
<div class='commit-title'>Change the output format provided by claude ai</div>
</li>
</ul>
</details>
</div>