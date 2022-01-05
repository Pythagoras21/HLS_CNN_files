# HLS_CNN_files
The uploaded files contain 
1. CNN model in h5 format
2. Weights 
3. Config.yaml
When building the model, it returns 

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

ERROR: [XFORM 203-504] Stop unrolling loop 'ConvOutHeight' (firmware/nnet_utils/nnet_conv2d_latency.h:195) in function 'nnet::conv_2d_latency_cl<ap_fixed<16, 6, (ap_q_mode)5, (ap_o_mode)3, 0>, ap_fixed<16, 6, (ap_q_mode)5, (ap_o_mode)3, 0>, config12>' because it may cause large runtime and excessive memory usage due to increase in code size. Please avoid unrolling the loop or form sub-functions for code in the loop body.
ERROR: [HLS 200-70] Pre-synthesis failed.
command 'ap_source' returned error code
    while executing
"source build_prj.tcl"
    ("uplevel" body line 1)
    invoked from within
"uplevel \#0 [list source $arg] "

INFO: [Common 17-206] Exiting vivado_hls at Mon Jan  3 14:15:10 2022...

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
