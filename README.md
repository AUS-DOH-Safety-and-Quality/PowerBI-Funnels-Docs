# PowerBI-Funnels-Docs

Development repository for testing changes to the PowerBI-Funnels documentation website.

Any changes made to the documentation in this repo will be rendered to: https://aus-doh-safety-and-quality.github.io/PowerBI-Funnels-Docs/

Once the updates are stable and ready to be used in the main website, update the submodule in the `PowerBI-Funnels` repo and commit the changes:

```sh
cd /path/to/PowerBI-Funnels
git submodule update --remote --merge
git commit -am "Update website"
git push
```

The main documentation website will then be rebuilt and published with the changes
