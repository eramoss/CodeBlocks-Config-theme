# how to set

## manually

just copy the content of file `dark.conf` inside of default.conf of CodeBlocks configs
at section

```XML
<editor>
...
</editor>
```

the section above can be changed completely for the content of the dark.conf file

## with cb share

in linux run `sudo cb_share_config` find the dark.conf file in application that opens
select default.conf and then transfer `<editor>` section to the file default.conf

---

in windows make sure that CodeBlocks are closed, and then execute the app `cb_share_config.exe`
a cv_share_config will open. Find the dark.conf file in source configuration file and
select default.conf on destination and then transfer `<editor>` section to the file default.conf
