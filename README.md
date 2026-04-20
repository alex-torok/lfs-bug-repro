Showcase how modifying .gitattributes can lead to nonreproducible checkouts with LFS

```
cat foo.txt

git checkout orphan_lfs_file
cat foo.txt

git checkout initial_commit
git checkout add_lfs_file
cat foo.txt

git checkout orphan_lfs_file
cat foo.txt
```
