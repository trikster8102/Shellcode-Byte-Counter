# Shellcode-Byte-Counter
A bash script that accepts a txt file with shellcode and returns the number of bytes of the shellcode

# How to Use
e.g. save your shellcode in a file as follows:


"\xbe\x93\xd6\x35\xa1\xda\xc6\xd9\x74\x24\xf4\x5a\x33\xc9\xb1"
"\x52\x31\x72\x12\x03\x72\x12\x83\x51\xd2\xd7\x54\xa9\x33\x95"
"\x97\x51\xc4\xfa\x1e\xb4\xf5\x3a\x44\xbd\xa6\x8a\x0e\x93\x4a"
"\x60\x42\x07\xd8\x04\x4b\x28\x69\xa2\xad\x07\x6a\x9f\x8e\x06"
"\xe8\xe2\xc2\xe8\xd1\x2c\x17\xe9\x16\x50\xda\xbb\xcf\x1e\x49"
"\x2b\x7b\x6a\x52\xc0\x37\x7a\xd2\x35\x8f\x7d\xf3\xe8\x9b\x27"
"\xd3\x0b\x4f\x5c\x5a\x13\x8c\x59\x14\xa8\x66\x15\xa7\x78\xb7"
"\xd6\x04\x45\x77\x25\x54\x82\xb0\xd6\x23\xfa\xc2\x6b\x34\x39"
"\xb8\xb7\xb1\xd9\x1a\x33\x61\x05\x9a\x90\xf4\xce\x90\x5d\x72"
"\x88\xb4\x60\x57\xa3\xc1\xe9\x56\x63\x40\xa9\x7c\xa7\x08\x69"
"\x1c\xfe\xf4\xdc\x21\xe0\x56\x80\x87\x6b\x7a\xd5\xb5\x36\x13"
"\x1a\xf4\xc8\xe3\x34\x8f\xbb\xd1\x9b\x3b\x53\x5a\x53\xe2\xa4"
"\x9d\x4e\x52\x3a\x60\x71\xa3\x13\xa7\x25\xf3\x0b\x0e\x46\x98"
"\xcb\xaf\x93\x0f\x9b\x1f\x4c\xf0\x4b\xe0\x3c\x98\x81\xef\x63"
"\xb8\xaa\x25\x0c\x53\x51\xae\x39\xaf\x59\x62\x56\xad\x59\x7b"
"\x1d\x38\xbf\x11\x71\x6d\x68\x8e\xe8\x34\xe2\x2f\xf4\xe2\x8f"
"\x70\x7e\x01\x70\x3e\x77\x6c\x62\xd7\x77\x3b\xd8\x7e\x87\x91"
"\x74\x1c\x1a\x7e\x84\x6b\x07\x29\xd3\x3c\xf9\x20\xb1\xd0\xa0"
"\x9a\xa7\x28\x34\xe4\x63\xf7\x85\xeb\x6a\x7a\xb1\xcf\x7c\x42"
"\x3a\x54\x28\x1a\x6d\x02\x86\xdc\xc7\xe4\x70\xb7\xb4\xae\x14"
"\x4e\xf7\x70\x62\x4f\xd2\x06\x8a\xfe\x8b\x5e\xb5\xcf\x5b\x57"
"\xce\x2d\xfc\x98\x05\xf6\x1c\x7b\x8f\x03\xb5\x22\x5a\xae\xd8"
"\xd4\xb1\xed\xe4\x56\x33\x8e\x12\x46\x36\x8b\x5f\xc0\xab\xe1"
"\xf0\xa5\xcb\x56\xf0\xef"

Run the script against the shellcode text file:
./shellcode_byte_counter.sh shellcode.txt
