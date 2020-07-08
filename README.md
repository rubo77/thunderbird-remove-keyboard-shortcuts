thunderbird-patch:

Removes most of the original keyboard shortcuts from Thunderbird
Unpacks `thunderbirds/omni.ja`, apply patches and then packs it back.

Either run this from the downloaded and unpacked Thunderbird directory,
or pass the path to that directory as the first argument.

On a system where thunderbird is installed as a package, pass it the
location of the thunderbird files, e.g. `/usr/lib64/thunderbird` on Opensuse
or `/usr/lib/thunderbird` on Ubuntu 20.04.

The tricky part is that sometimes updates break Thunderbird and you need to repatch it.

> WARNING: Sometimes re-patching is needed when Thunderbird updates itself and changes `omni.ja`
>   Re-patching an already patched version does not work!  The changes are already there.  
  You need to download new version of Thunderbird and then re-patch the `omni.ja` again!
