# Esp32-low-power-modes
Project to test out low power modes in Esp32

All examples were taken from: https://github.com/espressif/esp-idf

To setup environment, run this command:

```bash
docker run -it --rm --group-add=dialout --device=<esp32 device when connected> -v $PWD:/project -w /project -u $UID -e HOME=/tmp espressif/idf
```

and you will be able to build, flash and monitor like usual.
