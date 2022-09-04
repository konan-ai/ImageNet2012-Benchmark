# deploy-imagenet

### ImageNet2012 Deployment Evaluation Benchmarks

<table>
  
  <tr><td> Architecture </td>
      <td> Framework    </td>
      <td> Model        </td>
      <td> Logits       </td>
      <td> Size         </td> <td>% Diff</td>
      <td> Top-1        </td> <td>% Diff</td>
      <td> Top-5        </td> <td>% Diff</td>
      <td> Xent         </td> <td>% Diff</td>
  </tr>
  <tr><td>ResNet34</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>AlexNet</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-11</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-13</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-16</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-19</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-11 BN</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-16 BN</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>VGG-19 BN</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNet-18</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNet-34</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNet-50</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNet-101</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNet-152</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>SqueezeNet 1.0</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>SqueezeNet 1.1</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Densenet-121</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Densenet-169</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Densenet-201</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Densenet-161</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Inception V3</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>GoogleNet</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ShuffleNet V2</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>MobileNet V2</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNeXt-50-32x4d</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>ResNeXt-101-32x8d</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Wide ResNet-50-2</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>Wide ResNet-101-2</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
  </tr>
  <tr><td>MNASNet</td>
      <td> PyTorch (fp32)  <br> ONNX (int8) <br> ONNX (int8) </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> [Link]  <br> [Link] <br> [Link] </td>
      <td> X.XMB  <br> X.XMB  <br> X.XMB </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
      <td> XX.X    <br> XX.X    <br> XX.X   </td>
      <td> -        <br> XX.X    <br> XX.X   </td>
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

