# Learn Crux Datalog Today

Learn Crux Datalog Today is derived from the classic [learndatalogtoday.org](http://learndatalogtoday.org) tutorial materials, but adapted to focus on the [Crux](https://opencrux.com) API and unique Datalog semantics.

## Quickstart

Read the tutorial: https://nextjournal.com/learn-crux-datalog-today/learn-crux-datalog-today
Try online: https://nextjournal.com/try/learn-crux-datalog-today/learn-crux-datalog-today

## Installation

The easiest way to go through the tutorial is with either the "Read" or "Try" links presented in the Quickstart.
However, if you want to install the Markdown file from scratch, you can follow these instructions.
The outcome will be the same.

1. Create a new account on [Nextjournal](https://nextjournal.com).
2. Download [master.md](https://raw.githubusercontent.com/crux-labs/learn-crux-datalog-today/master/master.md).
3. Click "+ NEW" to create a new notebook on the [Nextjournal Dashboard](https://nextjournal.com/dashboard).
4. At the bottom of the page, choose "Import: Select a Markdown file to import" and upload `master.md` you downloaded in Step 2.
Do not use "Import from a (GitHub) URL" -- it will not work.
5. Once imported, scroll down to the EDN block which begins with `{:deps ...` under "Runtime Setup".
Hover your cursor over this EDN block and an ellipsis ("...") will appear on the lefthand side.
Click the ellipsis.
Choose "Assign Name" and enter `deps.edn`.
6. Open the Clojure Runtime Settings by clicking "Runtimes: Clojure" in the lefthand sidebar.
Scroll down to "Mounts" and click "+ Add mount".
Select `deps.edn`.
Click "Save changes and start" in the dialog that appears at the top.

You can now try the tutorial!
Use the "Run All" button at the top or the "Run Cell" buttons beside each Clojure snippet to execute the samples.

## Re-installation (for maintainers)

To reinstall the tutorial: Treat this GitHub repository as the golden store. Make edits to the Markdown file in
GitHub, then reimport the entire notebook using the following instructions.

1. Log in as the `learn-crux-datalog-today` Nextjournal user (ask @deobald, @refset, or @johantonelli for creds)
2. Go to the [Nextjournal Dashboard](https://nextjournal.com/dashboard)
3. Open the "Share" dialog (in the upper-right):
   1. Select "Notebook Visibility: Private"
   2. Select "Edit Slug" and change the slug to a name like `learn-crux-datalog-today-old-05` so it won't collide with the notebook you are about to import.
   3. Select "Published Version: Unpublish this notebook..."
7. Edit the title of the document to `"Learn Crux Datalog Today - Old05"` or something similar so it's easy to identify
in the list of archived notebooks.
8. Refresh the [Nextjournal Dashboard](https://nextjournal.com/dashboard). You should see `"Learn Crux Datalog Today - Old05"`
in the list. Select "Actions: Archive". (At present, you cannot completely delete a notebook.)
9. Follow the `"Installation"` instructions above, with the following additional steps from the "Share" dialog:
   1. Select "Notebook Visibility: Public"
   2. Select "Edit Slug" and change the slug to `learn-crux-datalog-today`
   3. Select "Publish Changes"
10. Check to make sure the public URLs in the `"Quickstart"` work correctly.

## Copyright & License

[Eclipse Public License - Version 1.0](https://github.com/crux-labs/learn-crux-datalog-today/blob/master/LICENSE.html)

© 2013 - 2016 Jonas Enlund

Thank you Jonas and contributors for freely licensing your excellent materials!
