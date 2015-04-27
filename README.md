# PNGExtract

Extract PNG images from (binary) files

## Usage

```
pngextract <binary file> [output filename]
```

### Example output
```
$ pngextract binary.bin

Found PNG #0
PNG written to binary.bin.0.png
Found PNG #1
PNG written to binary.bin.1.png
done
```

```
$ pngextract binary.bin output

Found PNG #0
PNG written to output.0.png
Found PNG #1
PNG written to output.1.png
done
```

## License

[WTPL](LICENSE.txt)