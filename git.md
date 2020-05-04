
# Git

## Commit Description

### Starter

#### `[ADD]`

Use if file(s) were added

#### `[CHANGE]`

Use if file(s) has been changed/edited/updated

#### `[REMOVE]`

Use if  file(s) were removed

#### `[FIX]`

Use if file(s) were not intentionally changed, but some issue was fixed

### Description

#### If `[ADD]`, `[REMOVE]`

Provide a name (or team-recognizable alias) for the affected file(s)

#### If  `[CHANGE]`,  `[FIX]`

Address or describe the resolved problem or the change of file(s)

## Commit Structure

 * Keep the commits atomic
	 * One commit should address one problem/change
	 * Split a larger commit into few small ones
	 * Ideally keep a commit as 1 changed file (+ 1 `*.meta` file)

 * **Important:** Include the `*.meta` file(s) corresponding to your original file(s) (if changed)
 * Do not include any changes that have nothing to do with the commit's intent
