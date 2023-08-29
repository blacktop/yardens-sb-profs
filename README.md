# yardens-sb-profs

> Output from running Yarden's sandblaster on an `iPhone15,2`'s **iOS17beta7** kernelcache

## Info

This was the output from running the following using [cellebrite-labs/sandblaster](https://github.com/cellebrite-labs/sandblaster)
    
```bash
❯ ipsw kernel sbopts 21A5319a__iPhone15,2/kernelcache.release.iPhone15,2 > 21A5319a__iPhone15,2/sbopts
```
```bash
❯ mkdir OUT
❯ python3 reverse_sandbox.py -r 17 21A5319a__iPhone15,2/sandbox_collection.bin -o 21A5319a__iPhone15,2/sbopts -d OUT
```

## Caveats

I haven't spoken to the developer yet and am not sure what state the code is in currently, so this output might not be a true representation of the sandbox profiles and could change.
 
So YMMV 