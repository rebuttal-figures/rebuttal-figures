

<img width="570" height="300" alt="cifar100" src="https://github.com/user-attachments/assets/76fa7316-05e1-43b0-9313-fd2b28e83553" />
<br>
Figure 1: The experimental results on CIFAR-100 under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br>
<img width="570" height="300" alt="resnet" src="https://github.com/user-attachments/assets/2055349a-e104-48f5-842b-57a11da9fa17" />
<br>
Figure 2: The experimental results on CIFAR-10 using ResNet-9 under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br>
<img width="570" height="300" alt="vit" src="https://github.com/user-attachments/assets/6469b8e8-0f50-4580-b9f1-d7c7490646ce" />
<br>
Figure 3: The experimental results on CIFAR-10 using ViT under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br>
<img width="570" height="300" alt="jichu" src="https://github.com/user-attachments/assets/58b377a7-02f7-4e38-8654-03f33e6dcdd7" />
<br>
Figure 4: The experimental results on CIFAR-10 using baseline CNN under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br>
<img width="570" height="300" alt="tau_low" src="https://github.com/user-attachments/assets/30ffba87-863f-48c2-b15b-9363e41b0952" />
<br>
Figure 5: The experimental results about $\tau_{low}$ of values {5,10,20,50}.
<br>
<img width="570" height="300" alt="tau" src="https://github.com/user-attachments/assets/fc6b1da3-0adb-4a42-add7-46f0de931360" />
<br>
Figure 6: The experimental results about the patience hyperparameter of values {50,100,150}.
<br>

<br>
<p><em>Table 1: Wall-clock time analysis (in seconds) and communication rounds required to achieve target global accuracies. 'N/A' indicates the algorithm failed to reach the target accuracy within the maximum 1600 rounds.</em></p>
<br>
<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="2">Target: 20% Acc</th>
      <th colspan="2">Target: 50% Acc</th>
      <th colspan="2">Target: 60% Acc</th>
      <th colspan="2">Target: 65% Acc</th>
      <th colspan="2">Total (1600 Rounds)</th>
    </tr>
    <tr>
      <th>FedRCO</th>
      <th>FedAvg</th>
      <th>FedRCO</th>
      <th>FedAvg</th>
      <th>FedRCO</th>
      <th>FedAvg</th>
      <th>FedRCO</th>
      <th>FedAvg</th>
      <th>FedRCO</th>
      <th>FedAvg</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Approximation Time (s)</td>
      <td align="center">0.12</td><td align="center">-</td>
      <td align="center">0.20</td><td align="center">-</td>
      <td align="center">0.31</td><td align="center">-</td>
      <td align="center">0.50</td><td align="center">N/A</td>
      <td align="center">13.12</td><td align="center">-</td>
    </tr>
    <tr>
      <td>Inverse Time (s)</td>
      <td align="center">5.04</td><td align="center">-</td>
      <td align="center">9.68</td><td align="center">-</td>
      <td align="center">15.83</td><td align="center">-</td>
      <td align="center">26.41</td><td align="center">N/A</td>
      <td align="center">737.97</td><td align="center">-</td>
    </tr>
    <tr>
      <td>Communication Time (s)</td>
      <td align="center">3.26</td><td align="center">31.93</td>
      <td align="center">12.15</td><td align="center">671.41</td>
      <td align="center">22.57</td><td align="center">1315.60</td>
      <td align="center">38.82</td><td align="center">N/A</td>
      <td align="center">1135.77</td><td align="center">1431.99</td>
    </tr>
    <tr>
      <td><strong>Total Time (s)</strong></td>
      <td align="center"><strong>27.61</strong></td><td align="center"><strong>97.84</strong></td>
      <td align="center"><strong>115.19</strong></td><td align="center"><strong>2530.93</strong></td>
      <td align="center"><strong>232.36</strong></td><td align="center"><strong>5309.16</strong></td>
      <td align="center"><strong>418.76</strong></td><td align="center"><strong>N/A</strong></td>
      <td align="center"><strong>11687.80<strong></td><td align="center"><strong>5808.76<strong></td>
    </tr>
    <tr>
      <td><strong>Comm. Rounds</strong></td>
      <td align="center"><strong>2</strong></td><td align="center"><strong>33</strong></td>
      <td align="center"><strong>14</strong></td><td align="center"><strong>750</strong></td>
      <td align="center"><strong>29</strong></td><td align="center"><strong>1469</strong></td>
      <td align="center"><strong>52</strong></td><td align="center"><strong>N/A</strong></td>
      <td align="center"><strong>1600<strong></td><td align="center"><strong>1600<strong></td>
    </tr>
  </tbody>
</table>
