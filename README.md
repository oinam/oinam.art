# [Oinam Art](https://oinam.art)



## NFT Images

- The low-resolution images are downsampled to 800x800 pixels from the top-center of the original NFT.
- Converted to webp for web consumption.
	+ Single File\
		`cwebp -q 60 file.jpg -o file.webp`
	+ Multiple files in recursive folders
		`for file in */*; do cwebp -q 60 "$file" -o "${file%.*}.webp"; done`