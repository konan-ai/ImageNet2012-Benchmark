# deploy-imagenet

### ImageNet2012 Deployment Evaluation Benchmarks
<table>
    <tr>
        <td>Architecture</td>
        <td>Framework</td>
        <td>Model</td>
        <td>Logits</td>
        <td>Size </td>
        <td>Size Difference</td>
        <td>Top1 Error</td>
        <td>Top1 Error Difference </td>
        <td>Top5 Error</td>
        <td>Top5 Error Difference</td>
    </tr>
    <tr>
        <td>squeezenet1_0</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/squeezenet1_0-b66bff10.pth">Link</a></td>
        <td><a href=" https://drive.google.com/file/d/17wsSLJC4kXnuYN5g4HH3xEuzy3aI7KM8/view?usp=sharing ">Link</a></td>
        <td> 4.88MB </td>
        <td>--</td>
        <td>41.91</td>
        <td>--</td>
        <td>19.58</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/106Ix1RS_s1irujC1-RQgvltOaQ3-rszg/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1ZjrEA4M47ryBa7kgxecBFylK17a9UeFw/view?usp=sharing">Link</a></td>
        <td>4.89MB</td>
        <td>-0.19%</td>
        <td>41.91</td>
        <td>0.00%</td>
        <td>19.58</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-8D5FNcjtDlQ5s5vMWA2WjH2KFsdjUFU/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1JyITMxww4Rn4eo0GeaL_BKG8UeIsBp3s/view?usp=sharing">Link</a></td>
        <td>1.27MB</td>
        <td>74.04%</td>
        <td>42.26</td>
        <td>-0.84%</td>
        <td>19.77</td>
        <td>-0.96%</td>
    </tr>
    <tr>
        <td>squeezenet1_1</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/squeezenet1_1-b8a52dc0.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1--RQw4nu8Hd3v0AQTmvJyfLLP7gks9e5/view?usp=sharing ">Link</a></td>
        <td>4.83MB</td>
        <td>--</td>
        <td>41.82</td>
        <td>--</td>
        <td>19.38</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-yDUvjSayX5lLZ5_vGekNmu05OJhuM-d/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-FqjUhoEbIpKIk3GBOe9Z8CxxxBhwmHj/view?usp=sharing">Link</a></td>
        <td>4.84MB</td>
        <td>-0.19%</td>
        <td>41.82</td>
        <td>0.00%</td>
        <td>19.38</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-6yyMpUDtc8kSIC17gaJunDeU11kqigy/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1--PqnMMfAeFKCockS2P998q-iNojVo-g/view?usp=sharing">Link</a></td>
        <td>1.26MB</td>
        <td>74.03%</td>
        <td>41.88</td>
        <td>-0.13%</td>
        <td>19.47</td>
        <td>-0.51%</td>
    </tr>
    <tr>
        <td>densenet121</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/densenet121-a639ec97.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-CU-FMlMd7NVjYbgWk51tUhLUkjPgFdV/view?usp=sharing">Link</a></td>
        <td>31.5MB</td>
        <td>--</td>
        <td>25.57</td>
        <td>--</td>
        <td>8.03</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/108Ozb1gDAsFxNXe3sZd1FtVPRychxTZz/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-KQOhbuFvvkIW2ZZOift7r0PmF_3i9bB/view?usp=sharing">Link</a></td>
        <td>31.49MB</td>
        <td>0.02%</td>
        <td>25.57</td>
        <td>0.00%</td>
        <td>8.03</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-3BEnMA69IjK-PKHw6HFC0DssQPGwMAr/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1yz1qOPScAyflRyovKv65uxnEaO6ZiqmO/view?usp=sharing">Link</a></td>
        <td>8.49MB</td>
        <td>73.06%</td>
        <td>27.53</td>
        <td>-7.67%</td>
        <td>9.18</td>
        <td>-14.30%</td>
    </tr>
    <tr>
        <td>densenet161</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/densenet161-8d451a50.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-GCy_q0vmptGj9TbEgfhjHUMQn-X5WOb/view?usp=sharing">Link</a></td>
        <td>112.9MB</td>
        <td>--</td>
        <td>22.86</td>
        <td>--</td>
        <td>6.44</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10DtRA09-zQUAVLsEICg32AxGyPNAdIKn/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-OKi4cAf307KSPHSjJiJhHBMBHOxavBV/view?usp=sharing">Link</a></td>
        <td>112.84MB</td>
        <td>0.05%</td>
        <td>22.86</td>
        <td>0.00%</td>
        <td>6.44</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-8XBo1mk_a8IxybNr478paWTUo9OnXTs/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-0POVymI9XhU1KOBku-3NtB5Nh_LdSIN/view?usp=sharing">Link</a></td>
        <td>29.62MB</td>
        <td>73.76%</td>
        <td>23.08</td>
        <td>-0.96%</td>
        <td>6.49</td>
        <td>-0.78%</td>
    </tr>
    <tr>
        <td>densenet169</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/densenet169-b2777c0a.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-JrbSncOBnLNMDTNz5XPyfWy8hBfoXVe/view?usp=sharing">Link</a></td>
        <td>55.9MB</td>
        <td>--</td>
        <td>24.40</td>
        <td>--</td>
        <td>7.19</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10Fy4GAFFXsqao_S_QivHZz0vk_z87HEr/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-DXXYLLn63FKvS9kcrkumVf_UugjSuqT/view?usp=sharing ">Link</a></td>
        <td>55.89MB</td>
        <td>0.00%</td>
        <td>24.40</td>
        <td>0.00%</td>
        <td>7.19</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-ACTWXl582arVeCh63sCSN632IryjHaj/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-ZAbRKRU5RIhPoB36iPsrYMotkbUltU3/view?usp=sharing">Link</a></td>
        <td>15.08MB</td>
        <td>73.03%</td>
        <td>24.75</td>
        <td>-1.43%</td>
        <td>7.34</td>
        <td>-2.09%</td>
    </tr>
    <tr>
        <td>densenet201</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/densenet201-c1103571.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-MXwh0okInK8zAGc2hd5-6S1T1rOdYfJ/view?usp=sharing ">Link</a></td>
        <td>79.08MB</td>
        <td>--</td>
        <td>23.10</td>
        <td>--</td>
        <td>6.63</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10Nl6Q0ZNktEHYwX89vKNHt125cJQYPl6/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-_eTfNgGUFnJfyn_EBnAk59GUirOQB6v/view?usp=sharing">Link</a></td>
        <td>79.09MB</td>
        <td>-0.01%</td>
        <td>23.10</td>
        <td>0.00%</td>
        <td>6.63</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-E8OPq4K-ntKgT6tNMca-GCi9IgJ2iws/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-Fpm1EnBdiajr3C5raGYn13aebsRaUpk/view?usp=sharing">Link</a></td>
        <td>21.33MB</td>
        <td>73.03%</td>
        <td>25.25</td>
        <td>-9.31%</td>
        <td>7.80</td>
        <td>-17.62%</td>
    </tr>
    <tr>
        <td>inception_v3</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/inception_v3_google-0cc3c7bd.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1Ww1CqVPYXLFV93wJYFjk4i1rkOY3Hs8F/view?usp=sharing">Link</a></td>
        <td>106.25MB</td>
        <td>--</td>
        <td>30.46</td>
        <td>--</td>
        <td>11.35</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10NzHEG6o2G0rln2Fvc9Rs9ypuRhrDu3u/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-bobTWyKIJtBhiUsqRRA4oiQ6BLxpDzU/view?usp=sharing ">Link</a></td>
        <td>93.07MB</td>
        <td>12.40%</td>
        <td>30.46</td>
        <td>0.00%</td>
        <td>11.35</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-Gw9uqpS-6K-HsFNSDjkXI3SPoFWHgox/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1AhK_OQwILZS5uDQqA6gD30ggnJXVqoCw/view?usp=sharing">Link</a></td>
        <td>23.44MB</td>
        <td>77.95%</td>
        <td>31.47</td>
        <td>-3.32%</td>
        <td>12.03</td>
        <td>-5.99%</td>
    </tr>
    <tr>
        <td>googlenet</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/googlenet-1378be20.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-5EAYKcfedM1P0v9sSGn5Ey_ehIbkBti/view?usp=sharing ">Link</a></td>
        <td>25.94MB</td>
        <td>--</td>
        <td>30.22</td>
        <td>--</td>
        <td>10.47</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10SuCXyAVwdo9KncZmwcGUimsj2aVQ5gi/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-h7TTzGDSdudpH5T07he80QxSNHIJvSp/view?usp=sharing">Link</a></td>
        <td>25.87MB</td>
        <td>0.26%</td>
        <td>30.22</td>
        <td>0.00%</td>
        <td>10.47</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-J6032_WHIvA0LlnEDwJ9kslgV1tsk13/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1--ngKdIMf8tbbSWihIeqlXF4OHpPIT9J/view?usp=sharing">Link</a></td>
        <td>6.56MB</td>
        <td>74.71%</td>
        <td>30.87</td>
        <td>-2.14%</td>
        <td>10.95</td>
        <td>-4.55%</td>
    </tr>
    <tr>
        <td>shufflenet_v2_x0_5</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/shufflenetv2_x0.5-f707e7126e.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-5FBWwFzpAdn3bT5dlcfSis78_9BmFUa/view?usp=sharing ">Link</a></td>
        <td>5.38MB</td>
        <td>--</td>
        <td>39.45</td>
        <td>--</td>
        <td>18.25</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10TpMOI7DFXnfEFpwGL3PdZTPy1jEAfxg/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-n_BToiLa7TlsKX1fGMo_psIHsVw0aed/view?usp=sharing">Link</a></td>
        <td>5.39MB</td>
        <td>-0.33%</td>
        <td>39.45</td>
        <td>0.00%</td>
        <td>18.25</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-dZ36U85W41znxBM57frufyfYRzKBuaE/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-5yatWyNWMNFmGI3wYq4rXGk8uQpFzEv/view?usp=sharing">Link</a></td>
        <td>1.46MB</td>
        <td>72.84%</td>
        <td>43.12</td>
        <td>-9.31%</td>
        <td>21.04</td>
        <td>-15.27%</td>
    </tr>
    <tr>
        <td>shufflenet_v2_x1_0</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/shufflenetv2_x1-5666bf0f80.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-EnSTMbCwA--Pam8MfOtmEkRKQ-BoccM/view?usp=sharing">Link</a></td>
        <td>8.97MB</td>
        <td>--</td>
        <td>30.64</td>
        <td>--</td>
        <td>11.68</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10aCvZMpUfDOXUQy8SAUZsko-GO0NGUgo/view?usp=sharing">Link</a></td>
        <td><a href=" https://drive.google.com/file/d/1-zEEUi-Aa2eFg_rz0nH_V10ZMRh1Pkiz/view?usp=sharing">Link</a></td>
        <td>8.94MB</td>
        <td>0.34%</td>
        <td>30.64</td>
        <td>0.00%</td>
        <td>11.68</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-cZ0-OhtTEpP78o2VQpANRG2hjuVIXVy/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-6o_QCKdEwwxWgrV1QYAEQflq5rfjYCd/view?usp=sharing">Link</a></td>
        <td>2.36MB</td>
        <td>73.71%</td>
        <td>34.52</td>
        <td>-12.69%</td>
        <td>14.16</td>
        <td>-21.21%</td>
    </tr>
    <tr>
        <td>shufflenet_v2_x1_5</td>
        <td>PyTorch (fp32)</td>
        <td><a href="">Link</a></td>
        <td><a href=" https://drive.google.com/file/d/1-GveoZOdeQvSJZRNcw4PVVaPxEOvexy5/view?usp=sharing">Link</a></td>
        <td>13.78MB</td>
        <td>--</td>
        <td>27.22</td>
        <td>--</td>
        <td>8.95</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10eHFVAZm-6dbOg6S8uzo3duZls1oOcU3/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/100gzdp9U-A2TdvPATDP7aazAVbDkkxo6/view?usp=sharing">Link</a></td>
        <td>13.71MB</td>
        <td>0.53%</td>
        <td>27.22</td>
        <td>0.00%</td>
        <td>8.95</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-PLwfYe8uolWNdOQ-NaRqykav1DN9WAX/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-GMXnLmHayBux8POuQ5V_e8Buq8y5nIm/view?usp=sharing">Link</a></td>
        <td>3.57MB</td>
        <td>74.16%</td>
        <td>28.78</td>
        <td>-5.72%</td>
        <td>9.81</td>
        <td>-9.66%</td>
    </tr>
    <tr>
        <td>shufflenet_v2_x2_0</td>
        <td>PyTorch (fp32)</td>
        <td><a href="">Link</a></td>
        <td><a href=" https://drive.google.com/file/d/1-JknAdp_5Pint6y8AYXLZPGmyzWiqhvd/view?usp=sharing ">Link</a></td>
        <td>29.02MB</td>
        <td>--</td>
        <td>23.79</td>
        <td>--</td>
        <td>7.12</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10eNh3q0aLWUIFD90JH9Xv5-k-jDxPLNR/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10Fn2yWSg3XWXamrU5nCr8qxG_zMnpNuV/view?usp=sharing">Link</a></td>
        <td>28.89MB</td>
        <td>0.46%</td>
        <td>23.79</td>
        <td>0.00%</td>
        <td>7.12</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-kD37mqZ_KYQW6Ih_gs2IgSt9Y-5GBa8/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-JpT2HqgqGFVv-QSLD_wHCztc6u-WqpR/view?usp=sharing">Link</a></td>
        <td>7.37MB</td>
        <td>74.60%</td>
        <td>27.41</td>
        <td>-15.23%</td>
        <td>9.02</td>
        <td>-26.74%</td>
    </tr>
    <tr>
        <td>mobilenet_v2</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/mobilenet_v2-b0353104.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-P7BAKLhIZ4VYYRhvX9eMoyizD3JToCi/view?usp=sharing ">Link</a></td>
        <td>13.83MB</td>
        <td>--</td>
        <td>28.12</td>
        <td>--</td>
        <td>9.71</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10lgT9WVrMJINb8vRIiUJ7CVWhbxrlL_x/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10HGxyHQOl6iVZVGQeqkqwBPK3jnWaTM1/view?usp=sharing">Link</a></td>
        <td>13.65MB</td>
        <td>1.31%</td>
        <td>28.12</td>
        <td>0.00%</td>
        <td>9.71</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-fbxhHQvHlTjRANavMifSSNI3_UzZWQ8/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-XBvN8v5tm4yFUWPYXsPC9U2t-29KQ4o/view?usp=sharing">Link</a></td>
        <td>3.53MB</td>
        <td>74.48%</td>
        <td>29.46</td>
        <td>-4.75%</td>
        <td>10.41</td>
        <td>-7.19%</td>
    </tr>
    <tr>
        <td>resnext50_32x4d</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/resnext50_32x4d-7cdf4587.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-QdtTXhDfyqcaaFfujar8iAlDSFddtCI/view?usp=sharing ">Link</a></td>
        <td>98.04MB</td>
        <td>--</td>
        <td>22.38</td>
        <td>--</td>
        <td>6.30</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10mawzsavXAAgzUH3r954-a8oPqC68IZC/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10HivNYtydJ-4TrrTinemuMGkd3cGBx2g/view?usp=sharing">Link</a></td>
        <td>97.66MB</td>
        <td>0.39%</td>
        <td>22.38</td>
        <td>0.00%</td>
        <td>6.30</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-kQVZ7aWSepVygKfOW0tu9aN10G2_qVR/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-ZLrzzCXkVCuUjJl_PoEvZJ8jwXKn7Hy/view?usp=sharing">Link</a></td>
        <td>24.59MB</td>
        <td>74.93%</td>
        <td>22.59</td>
        <td>-0.91%</td>
        <td>6.44</td>
        <td>-2.22%</td>
    </tr>
    <tr>
        <td>wide_resnet50_2</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/wide_resnet50_2-95faca4d.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-RXMriPkvQQFp7m9anCifVCAqyjalD-U/view?usp=sharing ">Link</a></td>
        <td>269.35MB</td>
        <td>--</td>
        <td>21.53</td>
        <td>--</td>
        <td>5.91</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10wXc5_JYAyBIGEHa3DsksSnPaVwldlBo/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10P5HOcWEINJMrrDxA_ym0ULBvCl9Ve0_/view?usp=sharing">Link</a></td>
        <td>268.96MB</td>
        <td>0.14%</td>
        <td>21.53</td>
        <td>0.00%</td>
        <td>5.91</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-pPSJrzqpq5MRS8bQAsOe416GvTR6fnl/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1sq7xKpjdQAiw0jd7zAI7ssygpiFh-ugg/view?usp=sharing">Link</a></td>
        <td>67.41MB</td>
        <td>74.97%</td>
        <td>21.60</td>
        <td>-0.32%</td>
        <td>5.95</td>
        <td>-0.64%</td>
    </tr>
    <tr>
        <td>wide_resnet101_2</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/wide_resnet101_2-32ee1156.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-Rdo3y0uV1INItEIumVao19YAdoC8zMA/view?usp=sharing ">Link</a></td>
        <td>496.2MB</td>
        <td>--</td>
        <td>21.15</td>
        <td>--</td>
        <td>5.72</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/10wi-I7gpvmS6zVvvTh-0K_Vqoa0xiblY/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10RIDWEM41-JBkmmXfG6NTMxbVmrj9__y/view?usp=sharing">Link</a></td>
        <td>495.42MB</td>
        <td>0.16%</td>
        <td>21.15</td>
        <td>0.00%</td>
        <td>5.72</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1-qwGhpISfPDyGv1RzqVStD0-GuRo6USN/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-4W_Vb_MAj6vwVOC8ttFGVYJimpyFJdl/view?usp=sharing">Link</a></td>
        <td>124.19MB</td>
        <td>74.97%</td>
        <td>21.35</td>
        <td>-0.95%</td>
        <td>5.83</td>
        <td>-1.99%</td>
    </tr>
    <tr>
        <td>mnasnet0_5</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/mnasnet0.5_top1_67.823-3ffadce67e.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-SM1VlRa2K8j2iVxxQSSrbO2ZD0ELBxB/view?usp=sharing ">Link</a></td>
        <td>8.75MB</td>
        <td>--</td>
        <td>32.26</td>
        <td>--</td>
        <td>12.51</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/116tzTowZty8BhyHv-Hjsov3JPMWvT6S7/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10RpLTbmoRj1EsKNaVTbdolitdGk-Z07D/view?usp=sharing">Link</a></td>
        <td>8.64MB</td>
        <td>1.23%</td>
        <td>32.26</td>
        <td>0.00%</td>
        <td>12.51</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/106aLwaGgY0LEjH-hrXr5Gdm_58ru_Efz/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1t-SIlXfPK3riN8RIeSvH79bUSu4s-HPY/view?usp=sharing">Link</a></td>
        <td>2.26MB</td>
        <td>74.22%</td>
        <td>99.90</td>
        <td>-209.65%</td>
        <td>99.50</td>
        <td>-695.51%</td>
    </tr>
    <tr>
        <td>mnasnet0_75</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/mnasnet0_75-7090bc5f.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-T9zuzsj7LQsE8MSptyS9p9bPXffJibf/view?usp=sharing ">Link</a></td>
        <td>12.51MB</td>
        <td>--</td>
        <td>29.12</td>
        <td>--</td>
        <td>9.85</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/111YtSP6RXWqzMLOG8u_RUgjVcXNbwqLw/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10UbB4MolHfQCmnHFwFw29rJIisr4v87-/view?usp=sharing">Link</a></td>
        <td>12.34MB</td>
        <td>1.29%</td>
        <td>29.12</td>
        <td>0.00%</td>
        <td>9.85</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/105ulggY_P5EU0bbuUYM8z8FjStpX5Z_-/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-8F8ITQQ-762TZRZC9vfUNvLfTUtvpW_/view?usp=sharing">Link</a></td>
        <td>3.2MB</td>
        <td>74.45%</td>
        <td>30.20</td>
        <td>-3.70%</td>
        <td>10.54</td>
        <td>-6.94%</td>
    </tr>
    <tr>
        <td>mnasnet1_0</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/mnasnet1.0_top1_73.512-f206786ef8.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-Vc7MMF0ZMFKAMV3qVgJ74k-bDrxG2Qp/view?usp=sharing ">Link</a></td>
        <td>17.28MB</td>
        <td>--</td>
        <td>26.54</td>
        <td>--</td>
        <td>8.49</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/112CtwDAvPATngraHN94I9DAMmGRdDbBW/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10c99GCZrx9DcQO_LgI2A8ExwXroaD2wp/view?usp=sharing">Link</a></td>
        <td>17.07MB</td>
        <td>1.21%</td>
        <td>26.54</td>
        <td>0.00%</td>
        <td>8.49</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1049KV3CCoLHcnfI873HNKkGghrVYBjCw/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-Bf2ZhvL7zs3XXvsEdrJL0rAPqO3njRj/view?usp=sharing">Link</a></td>
        <td>4.39MB</td>
        <td>74.60%</td>
        <td>28.32</td>
        <td>-6.69%</td>
        <td>9.45</td>
        <td>-11.33%</td>
    </tr>
    <tr>
        <td>mnasnet1_3</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/mnasnet1_3-a4c69d6f.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-fkZU_OryrYok_jJYjACPFxhzo4pxmty/view?usp=sharing ">Link</a></td>
        <td>24.74MB</td>
        <td>--</td>
        <td>23.92</td>
        <td>--</td>
        <td>6.70</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/113maElMITPshsyNfUq4PUTDszhRNDEba/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10jiFh1zLqm3ej0b4i3Ni9qFDEjN42s2e/view?usp=sharing">Link</a></td>
        <td>24.46MB</td>
        <td>1.10%</td>
        <td>23.92</td>
        <td>0.00%</td>
        <td>6.70</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10F_lVEAcRYlWWjj3_cPhZNbdBGYu0trf/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1horWiH2PoPGnUUYzfGO4Kc63dkarkNAK/view?usp=sharing">Link</a></td>
        <td>6.26MB</td>
        <td>74.72%</td>
        <td>25.23</td>
        <td>-5.46%</td>
        <td>7.47</td>
        <td>-11.49%</td>
    </tr>
    <tr>
        <td>alexnet</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/alexnet-owt-7be5be79.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-gRj2iPLsRf6mEUyWJfIELeHpSFzhuVK/view?usp=sharing ">Link</a></td>
        <td>238.68MB</td>
        <td>--</td>
        <td>43.48</td>
        <td>--</td>
        <td>20.93</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-KJwC5S0Bt0C3WmFGw68pKgWRn2vzKQd/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10k_U5yUY1PTegLSsT-muCHraTd-RlFqL/view?usp=sharing">Link</a></td>
        <td>238.68MB</td>
        <td>0.00%</td>
        <td>43.48</td>
        <td>0.00%</td>
        <td>20.93</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10IXdi4amU1YW546Y9A26CT4piZYvTiYf/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1--1LqQNww88ndQxrQvrJBw7Uo3hVYxoj/view?usp=sharing">Link</a></td>
        <td>59.71MB</td>
        <td>74.98%</td>
        <td>43.85</td>
        <td>-0.86%</td>
        <td>21.12</td>
        <td>-0.87%</td>
    </tr>
    <tr>
        <td>vgg11</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg11-8a719046.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-yAgER--KETogbO0O0esPtDFL8ptk98H/view?usp=sharing ">Link</a></td>
        <td>519MB</td>
        <td>--</td>
        <td>30.98</td>
        <td>--</td>
        <td>11.37</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-KWg1qz-U0iHhemdftrIjNwNnAPsd0Cn/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10q1-ffnlDHEDZgc3E9bsjLpplEi3zWXb/view?usp=sharing ">Link</a></td>
        <td>519.01MB</td>
        <td>0.00%</td>
        <td>30.98</td>
        <td>0.00%</td>
        <td>11.37</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10JSKoqNGPxhTdaxPBTiXb5b8eDXR7Q_d/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1DZrPUdRg48PHXlKSyCghpd2-Vz-gNXfw/view?usp=sharing">Link</a></td>
        <td>129.8MB</td>
        <td>74.99%</td>
        <td>31.02</td>
        <td>-0.14%</td>
        <td>11.36</td>
        <td>0.12%</td>
    </tr>
    <tr>
        <td>vgg11_bn</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg11_bn-6002323d.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10-qCgMZx47e5oGkxO7UWAb6I-Ei7Oq9G/view?usp=sharing ">Link</a></td>
        <td>519.05MB</td>
        <td>--</td>
        <td>29.63</td>
        <td>--</td>
        <td>10.19</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-PYNxpXYpSfLfl17Ry7yP62P1WMWgopH/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10rT6FGarmtrOuOFib1kMvXl6uUsyRbFd/view?usp=sharing ">Link</a></td>
        <td>519.01MB</td>
        <td>0.01%</td>
        <td>29.63</td>
        <td>0.00%</td>
        <td>10.19</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10NAoQAdZ6JanfANG5WIK6oqLifBKtEAy/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-2DMc-8E15SLOdIMFD5C7mxb3gL6hrmJ/view?usp=sharing">Link</a></td>
        <td>129.8MB</td>
        <td>74.99%</td>
        <td>29.86</td>
        <td>-0.78%</td>
        <td>10.35</td>
        <td>-1.55%</td>
    </tr>
    <tr>
        <td>vgg13</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg13-19584684.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10187bPwdK5wZILkBvh8-HZd6A5vEdP9R/view?usp=sharing ">Link</a></td>
        <td>519.72MB</td>
        <td>--</td>
        <td>30.07</td>
        <td>--</td>
        <td>10.75</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-U1XeDuF4XQHkjX8hUqSHdSE6DeqXXr1/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10rxLdRRKId6a7e7Px4E4mmIgpj12n5L1/view?usp=sharing ">Link</a></td>
        <td>519.73MB</td>
        <td>0.00%</td>
        <td>30.07</td>
        <td>0.00%</td>
        <td>10.75</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10SL5y3wuT8we_5W6WRr2WyVvdi0ApPPI/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-8KBiU6HdIuMcWTRapAB-IV9J4cc-OnG/view?usp=sharing ">Link</a></td>
        <td>129.99MB</td>
        <td>74.99%</td>
        <td>30.11</td>
        <td>-0.12%</td>
        <td>10.69</td>
        <td>0.56%</td>
    </tr>
    <tr>
        <td>vgg13_bn</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg13_bn-abd245e5.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/101qMiJvRKytcsyXKbPhtMXkTBPvrFSph/view?usp=sharing ">Link</a></td>
        <td>519.77MB</td>
        <td>--</td>
        <td>28.41</td>
        <td>--</td>
        <td>9.63</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-aFs0cL_3436r-8WU0_HJZ7lIOE00TQF/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10wbobOW8dlzkawm8zS0ZXgc9aTQhyOma/view?usp=sharing">Link</a></td>
        <td>519.73MB</td>
        <td>0.01%</td>
        <td>28.41</td>
        <td>0.00%</td>
        <td>9.63</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10Z2v403PtLDGMgin9oN6wVndngoL7QPn/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-9qOUYw27hylXUDJh16y79JdYt-B_p79/view?usp=sharing ">Link</a></td>
        <td>129.99MB</td>
        <td>74.99%</td>
        <td>28.71</td>
        <td>-1.06%</td>
        <td>9.77</td>
        <td>-1.48%</td>
    </tr>
    <tr>
        <td>vgg16</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg16-397923af.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1027a_z2gUqh3SHUx_tgTNlg-Qazb1Cdg/view?usp=sharing ">Link</a></td>
        <td>540.46MB</td>
        <td>--</td>
        <td>28.41</td>
        <td>--</td>
        <td>9.62</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-g6SIZ6sjoeA5x9qGELOsU56mV6iWK94/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/10zaElUf1V7dQ71CV0oyQhfgTjH4BY8uu/view?usp=sharing ">Link</a></td>
        <td>540.47MB</td>
        <td>0.00%</td>
        <td>28.41</td>
        <td>0.00%</td>
        <td>9.62</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10bIItZ-a7MMsLScp_4uiR_ZoQHg3xd7k/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-4jK0kPfaUz8x5kSHe78JW0xK8Ur1KDR/view?usp=sharing ">Link</a></td>
        <td>135.18MB</td>
        <td>74.99%</td>
        <td>28.43</td>
        <td>-0.09%</td>
        <td>9.61</td>
        <td>0.10%</td>
    </tr>
    <tr>
        <td>vgg16_bn</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg16_bn-6c64b313.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/103mHv3Lrw5npzMghh3UpCb7pFSZ7SBlW/view?usp=sharing ">Link</a></td>
        <td>540.53MB</td>
        <td>--</td>
        <td>26.64</td>
        <td>--</td>
        <td>8.48</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-juNiBGJyokt-6QBQT734TbKklJiqZjh/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/110U03PuaCaKN42DPpSFNkpVxL8Czjzv9/view?usp=sharing">Link</a></td>
        <td>540.47MB</td>
        <td>0.01%</td>
        <td>26.64</td>
        <td>0.00%</td>
        <td>8.48</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10cVf-Dxa1MG-SoBM_9xf7-IbEgKMge2E/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-5VCw8s45_ftHF4cdtS0Bpw3RIGcBvYA/view?usp=sharing ">Link</a></td>
        <td>135.18MB</td>
        <td>74.99%</td>
        <td>27.42</td>
        <td>-2.95%</td>
        <td>8.81</td>
        <td>-3.87%</td>
    </tr>
    <tr>
        <td>resnet18</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/resnet18-5c106cde.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-ipLezDfQArdeawjIVo1IXHuuD3D_5d9/view?usp=sharing ">Link</a></td>
        <td>45.7MB</td>
        <td>--</td>
        <td>30.24</td>
        <td>--</td>
        <td>10.92</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-roY611yUfph9WlnGvQ-9dENgrDg7Thu/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/11FX8M_5Ho5dtem5oCFplD9o8qETnzLO-/view?usp=sharing">Link</a></td>
        <td>45.65MB</td>
        <td>0.11%</td>
        <td>30.24</td>
        <td>0.00%</td>
        <td>10.92</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10gXzLIDyn85ik6k4VcNmVh2mjcoCct0k/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1Q8-pNOTqNbSVGVLXdGhvyI-jQG-PKfad/view?usp=sharing">Link</a></td>
        <td>11.46MB</td>
        <td>74.93%</td>
        <td>30.58</td>
        <td>-1.11%</td>
        <td>11.06</td>
        <td>-1.23%</td>
    </tr>
    <tr>
        <td>resnet34</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/resnet34-333f7ec4.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-ksaI04Hfnhvk-DAW7sVIp2bxOrcJJK7/view?usp=sharing ">Link</a></td>
        <td>85.22MB</td>
        <td>--</td>
        <td>26.69</td>
        <td>--</td>
        <td>8.58</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-sI3Gj45KIeg8ShZszxn5jT-sA_Hc3zR/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/11HHtRQ1KEfD2CdDl4QFAqiumFi5-3hIe/view?usp=sharing">Link</a></td>
        <td>85.13MB</td>
        <td>0.10%</td>
        <td>26.69</td>
        <td>0.00%</td>
        <td>8.58</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10jhQ3vd8KoO_VVa3-U9W6wgvfkTR9fpW/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-LGs_cgSje6w3UIcVj78_MPfqibCqQaC/view?usp=sharing">Link</a></td>
        <td>21.36MB</td>
        <td>74.94%</td>
        <td>26.96</td>
        <td>-1.03%</td>
        <td>8.73</td>
        <td>-1.77%</td>
    </tr>
    <tr>
        <td>resnet50</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/resnet50-19c8e357.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-mMGdbnylUC5EiLk1svorGRVQbuvKBLk/view?usp=sharing ">Link</a></td>
        <td>100.05MB</td>
        <td>--</td>
        <td>23.87</td>
        <td>--</td>
        <td>7.14</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-uo4yhTH90AAkybIbUrySbTNlnCNq9aW/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/11NA_t2O38qZ2Pk5R7zMvfJX8jF7mslO8/view?usp=sharing">Link</a></td>
        <td>99.75MB</td>
        <td>0.30%</td>
        <td>23.87</td>
        <td>0.00%</td>
        <td>7.14</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10klQ2AEWbGsf3WGUaCqM74qxdw02i6cZ/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-RHimrX5-VKJFxt2Jpt7WueTvTb7D-_j/view?usp=sharing">Link</a></td>
        <td>25.09MB</td>
        <td>74.93%</td>
        <td>24.47</td>
        <td>-2.53%</td>
        <td>7.39</td>
        <td>-3.59%</td>
    </tr>
    <tr>
        <td>resnet152</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/resnet152-b121ed2d.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-mO30nOLGlmnQXQzn7GdbAj5HQmaViWV/view?usp=sharing">Link</a></td>
        <td>235.73MB</td>
        <td>--</td>
        <td>21.69</td>
        <td>--</td>
        <td>5.95</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-xm8OawFzikqDPzmZJYTAB80rWwo4kXN/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/16UwFHnyzmuilaOgJ79HVIOBjwmdq5ihz/view?usp=sharing">Link</a></td>
        <td>234.88MB</td>
        <td>0.36%</td>
        <td>21.69</td>
        <td>0.00%</td>
        <td>5.95</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/1--XnvFYKYuGyeipdMmkd9RXlGEj9ZqXC/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-3Ylq4Yg5k5BbDeLZ9ycusoFclUNQDaV/view?usp=sharing">Link</a></td>
        <td>59.14MB</td>
        <td>74.91%</td>
        <td>21.78</td>
        <td>-0.43%</td>
        <td>6.02</td>
        <td>-1.07%</td>
    </tr>
    <tr>
        <td>resnet101</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/resnet101-5d3b4d8f.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-v6LB2b0pCZ8ZynJtD5ke5C8hWPw4Cai/view?usp=sharing ">Link</a></td>
        <td>174.44MB</td>
        <td>--</td>
        <td>22.63</td>
        <td>--</td>
        <td>6.45</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-v0iyrEJW2_2KxJ73mma3vtaj-nmIH8E/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-1oNWCizCh6w4SDs5A0OiW5xjkdwRBTb/view?usp=sharing">Link</a></td>
        <td>173.85MB</td>
        <td>0.34%</td>
        <td>22.63</td>
        <td>0.00%</td>
        <td>6.45</td>
        <td>0.00%</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10rWq5mEx1en7TEI0WeANzUNdnAtrs8ON/view?usp=sharing">Link</a></td>
        <td><a href="https://drive.google.com/file/d/1-6Yu7d9VqN8DFvdB91dBRJicVH8WDlS8/view?usp=sharing">Link</a></td>
        <td>43.75MB</td>
        <td>74.92%</td>
        <td>22.90</td>
        <td>-1.19%</td>
        <td>6.51</td>
        <td>-0.93%</td>
    </tr>
    <tr>
        <td>vgg19</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg19-dcbb9e9d.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/106N4F0ITItbjPkkcUG5a3eOuDVpP5_5l/view?usp=sharing ">Link</a></td>
        <td>--MB</td>
        <td>--</td>
        <td>28.41</td>
        <td>--</td>
        <td>9.62</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-n51OYH0gPByW5pkLosQxbDKr_bCRMY6/view?usp=sharing">Link</a></td>
        <td><a href="">Link</a></td>
        <td>--MB</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10dIna-YgpNBFmQkqQgBEJcWYlwNp0_Kl/view?usp=sharing">Link</a></td>
        <td><a href="">Link</a></td>
        <td>--MB</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td>vgg19_bn</td>
        <td>PyTorch (fp32)</td>
        <td><a href="https://download.pytorch.org/models/vgg19_bn-c79401a0.pth">Link</a></td>
        <td><a href="https://drive.google.com/file/d/108Tp_YIEo6uYilzjufHgmIa5tRPPfRBF/view?usp=sharing ">Link</a></td>
        <td>--MB</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (fp32)</td>
        <td><a href="https://drive.google.com/file/d/1-r1Oe4X6M-p2VoRrmQ6hwSetMGuSSyGu/view?usp=sharing">Link</a></td>
        <td><a href="">Link</a></td>
        <td>--MB</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
    </tr>
    <tr>
        <td></td>
        <td>Onnx (Int8)</td>
        <td><a href="https://drive.google.com/file/d/10faTqcCCuMAtFGzUT7ishdvDpU2Qau58/view?usp=sharing">Link</a></td>
        <td><a href="">Link</a></td>
        <td>--MB</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
        <td>--</td>
    </tr>
</table>


<!---------------------------------
TODO: Make cleaner column header
TODO: Add Results 
---------------------------------->

### PyTorch Model Loading
```
# TODO: Add code
```

### PyTorch Model Pre-processing
```
# TODO: Add code
```

### PyTorch Inference Example
```
# TODO: Add code
```

