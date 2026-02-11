## Installation:

Clone using `git lfs`:
```bash
git lfs install
git clone https://github.com/Jerom356/erhai-firmware --depth=1
cd erhai-firmware
git lfs pull
```

Install them to `/usr/lib/firmware/`
```bash
rm README.md
cp * -r /lib/firmware/
```

And you will be good to go!

> [!NOTE]
> Firmeare files based on `OPD2415_16.0.1.302(EX01)_IN`
