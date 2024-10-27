# rtt_playSound
Bird repeller with IoT capability via playing sound with RT-Thread IoT OS

# Introduction

this is originally targeted for contest https://rt-thread.medium.com/rt-thread-global-embedded-electronic-design-contest-f924605fb6f3
but because i eventually receive the board pretty late, not enough time to finish it to my original planning

the original intention is 
bird like pigeon is a nuisance to condominium dwellers where they shit and dirty they place outside of windows, for example on air conditional outdoor compressor unit. this project uses sensor to detect the presence of bird then play sound that repels the bird. we will have different recorded sounds like fire cracker, people shouting, cat noise to randomly play to expel bird. successful expel of brid is saved in log and can be examined by user using wifi

# System Diagram

# Setup
follow [1] 
since i use the wifi module, which needs 1.8V, we need to painstakingly change the resistor on Psoc6-evaluationkit-062S2

# Conclusion

# References
[1] [Setup instruction (in Chinese)](https://www.rt-thread.org/document/site/#/rt-thread-version/rt-thread-standard/hw-board/ifx-eval-kit/ifx-eval-kit)
[2] [BLE example](https://github.com/RT-Thread-Studio/sdk-bsp-cy8c624-infineon-evaluationkit/tree/main/projects/cyw43012_ble_demo)
[3] [WIFI example](https://club.rt-thread.org/ask/article/74bb091d04751d5a.html)
[4] [developer guide](https://docs.qq.com/doc/DZmpvR0xocFpVVGhQ)
[5] [markdown file creating link](https://anvilproject.org/guides/content/creating-links)
