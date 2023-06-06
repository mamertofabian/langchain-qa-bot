## Set up

### Mirroring the website

#### Mirror the blog site
```
wget --mirror --convert-links --adjust-extension --page-requisites --no-parent https://python./en/latest/index.html
```

### Creating the Indexes
Execute the notebook `create_indexes.ipynb` to create the indexes for the blog, main and help sites.
This will also create a merged index for all three sites and saved in the `index` folder.
