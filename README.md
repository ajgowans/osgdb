
# Obscure Systems Games DB for MiSTer

This is a Database that will help you get a few console and computer game and software collections for more obscure systems that are compatible with MiSTer cores.

### How to install

Add an entry to the `downloader.ini` file on the root of your SD (create it if it doesn't exist), to use it with the [MiSTer Downloader](https://github.com/MiSTer-devel/Downloader_MiSTer/) (which is what Update All calls under the hood). For that, please add the following entry there:

```
[bios_db]
db_url = https://raw.githubusercontent.com/ajgowans/osgdb/db/bios_db.json
```

Once you've done this, next time you run downloader, the files will get installed too.
