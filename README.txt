Alpine Linux VM for Cloudflare Pages

This ZIP is ready to upload to Cloudflare Pages. The structure:

/index.html          -> VM launcher
/bios/seabios.bin    -> BIOS (add actual file)
/bios/vgabios.bin    -> VGA BIOS (add actual file)
/images/alpine.img   -> Persistent disk image (add actual Alpine disk)
/v86.js              -> v86 JS library
/v86.wasm            -> v86 WebAssembly binary

Instructions:
1. Upload all contents to a Cloudflare Pages project.
2. Open index.html in browser.
3. Disk changes persist via IndexedDB.