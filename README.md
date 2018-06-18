# PS3 Voice and Graphics Patch (in progress)

Currently hosting only the automated placed lines. All files need manual fixing, avoid placing them on your game.

README's going to be updated as the patch is developed. Refer to our [wiki](https://github.com/07th-mod/guide/wiki) for more details about the patch.

Old collaborators welcome to join the repository, however it's still preferred to fork the repository and update through pull requests.

# Scripts progress

> **Everything is done!** The scripts are now entering bugfixing.

- [x] _tsum_001.txt
- [x] _tsum_002_1.txt
- [x] _tsum_002_2.txt
- [x] _tsum_003_1.txt
- [x] _tsum_003_2.txt
- [x] _tsum_003_3.txt
- [x] _tsum_003_4.txt
- [x] _tsum_004.txt
- [x] _tsum_005.txt
- [x] _tsum_006.txt
- [x] _tsum_007.txt
- [x] _tsum_008.txt
- [x] _tsum_009.txt
- [x] _tsum_010.txt
- [x] _tsum_011.txt
- [x] _tsum_012_1.txt
- [x] _tsum_012_2.txt
- [x] _tsum_013.txt
- [x] _tsum_014.txt
- [x] _tsum_015_1.txt
- [x] _tsum_015_2.txt
- [x] _tsum_016.txt
- [x] _tsum_017.txt
- [x] _tsum_018.txt
- [x] _tsum_019.txt
- [x] _tsum_020.txt
- [x] _tsum_021.txt
- [x] _tsum_022.txt
- [x] _tsum_023_1.txt
- [x] _tsum_023_2.txt
- [x] _tsum_024_1.txt
- [x] _tsum_024_2.txt
- [x] _tsum_025.txt
- [x] _tsum_026.txt
- [x] _tsum_op.txt
- [x] _tsum_tips_001.txt
- [x] _tsum_tips_002.txt
- [x] _tsum_tips_003.txt
- [x] _tsum_tips_004.txt
- [x] _tsum_tips_005.txt
- [x] _tsum_tips_006.txt
- [x] _tsum_tips_007.txt
- [x] _tsum_tips_008.txt
- [x] _tsum_tips_009.txt
- [x] _tsum_tips_010.txt
- [x] _tsum_tips_011.txt
- [x] _tsum_tips_012.txt
- [x] _tsum_tips_013.txt
- [x] _tsum_tips_014.txt

# Known issues (for fixing)

- [x] in _tsum_001.txt, line 248 slightly mismatches. Might be unchanged on PS2
- [x] in _tsum_001.txt, line 770 has no voice (for some reason)
- [x] in _tsum_002_2.txt, lines 253 to 271 have no voices
- [x] in _tsum_003_3.txt, line 938 has no voice. Most likely on PS2
- [x] in _tsum_005.txt, line 1144 has no voice. Looks like a random cut that might be in the PS2 voices
- [x] in _tsum_006.txt, lines 404 to 419 are missing a few voices. Text was toned down a bit
- [ ] in _tsum_007.txt, big chunks of the script has no voices (especially the first 1000 lines). Search for ``PlaySE(4, "", 128, 64);`` for all of them
- (unfixable) in _tsum_008.txt, line 1932, the text was changed from "I'm pregnant" to "He's proposed to me" (paraphrasing, of course). PS2 might have the correct voice
- (unfixable) in _tsum_008.txt, lines 1982 and 1988, both voices were changed to match the previous change. Same PS2 case might applies here
- (unfixable) in _tsum_008.txt, line 2014, line has no voice because it was toned down
- (unfixable) in _tsum_009.txt, line 34, the voice was changed to match the change made in the previous chapter (_tsum_008.txt, line 1932)
- (pretty much unfixable unless hidden somewhere) in _tsum_010.txt, line 2038 for some reason is not voiced
- [x] in _tsum_010.txt, line 2358 was cut from the PS3 release
- [x] in _tsum_011.txt, line 1486 doesn't entirely match with the PS3 script
- [x] in _tsum_011.txt, lines 1647, 1667, 1673, 1762, 1765, 1768, 2002 are for some reason absent in the PS3 release
- [x] in _tsum_013.txt, line 1630 was toned down. PS2 is probably uncensored
- [x] in _tsum_016.txt, lines 799, 802 and 810 were cut from the PS3 release
- [x] in _tsum_016.txt, lines 823, 827 and 1684 were toned down significantly
- [x] in _tsum_020.txt, lines 1620 and 1623 were cut from the PS3 release
- (unfixable - only 2101 was more or less fixed) in _tsum_021.txt, lines 2050, 2068 and 2101 was toned down significantly
- [x] in _tsum_021.txt, lines 2090 and 2093 were cut from the PS3 release
- [x] in _tsum_022.txt, lines 925 and 1443 were cut from the PS3 release
- [x] in _tsum_023_1.txt, line 538 was changed in the console release
- [x] in _tsum_024_1.txt, lines 935 to 964 have no voices
- [x] in _tsum_025.txt, line 388, for some reason the laugh is unvoiced
- [x] in _tsum_025.txt, lines 4797 to 4806 are unvoiced
- [ ] in _tsum_026.txt, line 108 was toned significantly
- [ ] in _tsum_026.txt, lines 168 and 171 were cut from the PS3 release
- [x] in _tsum_026.txt, line 609 was cut for some reason
- [ ] in _tsum_tips_014.txt, lines 683 to 694 were cut from the PS3 release