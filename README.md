
> [!NOTE] Cloning this repository
>
> This repository uses [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) for it's themes, so pass `--recurse-submodules` to the `git clone` command:
>
> ```shell
> git clone https://blah/blah.git --recurse-submodules
> ```
>
> If you forget to do this, it's ok.
>
> Just run:
> ```shell
> git submodule init
> git submodule update
> ```

# Hugo

This is a static website powered by [Hugo](https://gohugo.io).

## Hugo Installation

[Installation of Hugo](https://gohugo.io/installation/windows/) is easy.  I used `winget`:

```PowerShell
winget install Hugo.Hugo.Extended
```
## Hugo - Add content

To add a page called "Hello World":

```PowerShell
hugo new content content/posts/hello-world.md
```

## Hugo - Run

To serve locally, run the following and go to https://localhost:1313
```PowerShell
hugo server
```

To include articles in DRAFT status:
```PowerShell
hugo server -D
```
