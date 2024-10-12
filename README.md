# Hjosjmb
Hi,kids,6547,hf
keszybz:environment-generatorsFAIL: test-env-util
===================


=================================================================
==17489==ERROR: LeakSanitizer: detected memory leaks

Direct leak of 16 byte(s) in 1 object(s) allocated from:
    #0 0x7fd06fa1de60 in malloc (/lib64/libasan.so.3+0xc6e60)
    #1 0x7fd06ef1c5ec in malloc_multiply src/basic/alloc-util.h:70
    #2 0x7fd06ef1dc76 in strnappend src/basic/string-util.c:206
    #3 0x7fd06ef7efb0 in replace_env_n src/basic/env-util.c:694
    #4 0x55a386b954a7 in replace_env src/basic/env-util.h:42
    #5 0x55a386b978ba in test_replace_env src/test/test-env-util.c:160
    #6 0x55a386b99b24 in main src/test/test-env-util.c:324
    #7 0x7fd06d7e5400 in __libc_start_main (/lib64/libc.so.6+0x20400)

Direct leak of 9 byte(s) in 1 object(s) allocated from:
    #0 0x7fd06fa1de60 in malloc (/lib64/libasan.so.3+0xc6e60)
    #1 0x7fd06ef1c5ec in malloc_multiply src/basic/alloc-util.h:70
    #2 0x7fd06ef1dc76 in strnappend src/basic/string-util.c:206
    #3 0x7fd06ef7efb0 in replace_env_n src/basic/env-util.c:694
    #4 0x55a386b954a7 in replace_env src/basic/env-util.h:42
    #5 0x55a386b978ba in test_replace_env src/test/test-env-util.c:160
    #6 0x55a386b99b2e in main src/test/test-env-util.c:325
    #7 0x7fd06d7e5400 in __libc_start_main (/lib64/libc.so.6+0x20400)

SUMMARY: AddressSanitizer: 25 byte(s) leaked in 2 allocation(s).
FAIL test-env-util (exit status: 1)releases/3.4.7-beta2Shizuku-API/tree/master/demo) for more.
