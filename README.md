# satis

Clone this repository

```bash
git clone git@github.com:aquarelle/satis
```

Install satis

```bash
composer create-project composer/satis --stability=dev --keep-vcs
```

Build the project

```bash
./satis/bin/satis build project.json docs/
```

Update a single component

```bash
./satis/bin/satis build project.json docs/ --repository-url=git@github.com:aquarelle-cms/custom-components.git
```

After update

```bash
# add new files
git add .
# commit changes
git commit -am "Updated"
#push changes
git push origin master
```