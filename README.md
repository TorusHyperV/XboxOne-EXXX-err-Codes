# XboxOne-E-err-Codes
Documentation of Xbox One EXXX (E201, E105, etc...) error codes and their meaning, plus possible solutions

## Contribute
[Click here to contribute new error codes information](https://github.com/TorusHyperV/XboxOne-E-err-Codes/issues/new)

## Preamble
Xbox One shows two types of critical error codes when the console cannot boot. This list aims to become a comprehensive documentation of these codes, and advice or tutorials explaining how to repair consoles with those errors. 
**NOTE 1:** Some of these codes might be shared with Series S/X but the meanings might be slightly different! For example, Series S/X uses SSD, not HDD. Please always double check.
**NOTE 2:** Some official documentation exists (https://support.xbox.com/en-US/help/errors/error-code-e105) but usually the explanations are just vague or completely inaccurate. 

## Error Screen types
There are only 2 types of error screens that show EXXX codes.

<p align="center">
Screen Type 1:
</p>

If you see this screen type, it means that the Operating System has, at least, been able to start. But then it found some problems.
The Operating System can have started just from eMMC NAND memory (in the case of Xbox One) or from the SSD's hidden partition (in the case of Xbox Series)
The Operating System might have also loaded the full Operating System files from the HDD/SSD before failing.
![image](https://github.com/TorusHyperV/XboxOne-E-err-Codes/assets/100166926/5d67c9db-cf28-42af-95d9-0c7ad63fff18)

---

<p align="center">
Screen Type 2:
</p>

If you see this screen you are screwed. This is a bootloader screen, which means the OS didn't load. This means the bootloader was not able to read the basic OS files from the eMMC memory (in the case of Xbox One) or from the SSD's hidden partition (Xbox Series), or they were corrupted or some file missing.
![image](https://github.com/TorusHyperV/XboxOne-E-err-Codes/assets/100166926/b4b2684b-9c0f-4df0-b4d3-9fdb81fa34fb)

## E100 Codes
### E100
_Update Failed / Dvd drive not paired_

### E101:
Unknown/Pending Documentation

### E102:
Unknown/Pending Documentation

### E103:
Unknown/Pending Documentation

### E104:
Unknown/Pending Documentation

### E105:
_No HDD was found_

**Solutions:** Plug an HDD into the sata port. Check that the sata port is not damaged.

### E106:
_Update process failed do to a failed read/write to the Xbox One's eMMC._

**Solutions:** Try to dump eMMC, and then replace eMMC with a new part. Restore dump into the new eMMC. [VIDEO](https://www.youtube.com/watch?v=XJVitvPhe_M)
**Note:** The original eMMC must be readable enough to get the console's certificate. The rest of the memory is not necessary, but an Xbox One won't work without its factory-issued unique console certificate.

### E107:
Unknown/Pending Documentation

### E108:
Unknown/Pending Documentation

### E109:
Unknown/Pending Documentation

### E110:
Unknown/Pending Documentation

---

## E200 Codes
### E201:
Unknown/Pending Documentation

### E202:
Unknown/Pending Documentation

### E203:
Unknown/Pending Documentation

### E204:
Unknown/Pending Documentation

### E205:
Unknown/Pending Documentation

### E206:
Unknown/Pending Documentation

### E207:
Unknown/Pending Documentation

### E208: 
Unknown/Pending Documentation

### E209:
Unknown/Pending Documentation

### E210: 
Unknown/Pending Documentation

## Miscellaneous / Other information
Presumably, when rogue Xbox One Internal devkits are banned, they present an irreversible `E20X` error code. (Their certificate might be wipped, according to @TitleOS)
