# Architecture to run Accelerometer based ML data on ESP32 s3

* Data Extraction (from csv or pkl files)
* Data Pre-Processing (Spectral features)
* Reference: <https://docs.edgeimpulse.com/docs/edge-impulse-studio/processing-blocks/audio-mfe>
            <https://github.com/edgeimpulse/processing-blocks/tree/master/spectral_analysis>
                 (Need to find equivalent C++ code)
* Running ML model on features
* Similar to this: https://github.com/alibukharai/Blogs/blob/main/ESP-DL/model_development/model_development.ipynb

# Re-Writing Pre-Processing Algorithms in C

## Reference
* [https://github.com/edgeimpulse/inferencing-sdk-cpp](General Info)
* [https://github.com/edgeimpulse/inferencing-sdk-cpp/blob/master/dsp/numpy.hpp](Numpy Implementation)
* [https://github.com/ARM-software/CMSIS-DSP](ARM CMSIS-DSP Implementation)
  * [https://arm-software.github.io/CMSIS-DSP/latest/](Documentaiton for Above Repo)
* 
