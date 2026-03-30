

<img width="570" height="300" alt="cifar100" src="https://github.com/user-attachments/assets/76fa7316-05e1-43b0-9313-fd2b28e83553" />
<br>
Figure 1: The experimental results on CIFAR-100 under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br><br><br>
<img width="570" height="300" alt="resnet" src="https://github.com/user-attachments/assets/2055349a-e104-48f5-842b-57a11da9fa17" />
<br>
Figure 2: The experimental results on CIFAR-10 using ResNet-9 under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br><br><br>
<img width="570" height="300" alt="vit" src="https://github.com/user-attachments/assets/6469b8e8-0f50-4580-b9f1-d7c7490646ce" />
<br>
Figure 3: The experimental results on CIFAR-10 using ViT under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br><br><br>
<img width="570" height="300" alt="jichu" src="https://github.com/user-attachments/assets/58b377a7-02f7-4e38-8654-03f33e6dcdd7" />
<br>
Figure 4: The experimental results on CIFAR-10 using baseline CNN under the Dirichlet-non 0.1 setting with client number 100, and the party ratio 0.8.
<br><br><br>
<img width="570" height="300" alt="tau_low" src="https://github.com/user-attachments/assets/30ffba87-863f-48c2-b15b-9363e41b0952" />
<br>
Figure 5: The experimental results about $\tau_{low}$ of values {5,10,20,50}.
<br><br><br>
<img width="570" height="300" alt="tau" src="https://github.com/user-attachments/assets/fc6b1da3-0adb-4a42-add7-46f0de931360" />
<br>
Figure 6: The experimental results about the patience hyperparameter of values {50,100,150}.
<br>
<br>
<br>
<p><em>Table 1: Wall-clock time analysis (in seconds) and communication rounds required to achieve target global accuracies. 'N/A' indicates the algorithm failed to reach the target accuracy within the maximum of 1600 rounds.</em></p>
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

<br>
<p><em>Table 2: The experimental results on CIFAR-10 under the Dirichlet-non, Pathological-non, and IID settings with client number 100, and the party ratio 0.8 (%).</em></p>
<table>
  <thead>
    <tr>
      <th rowspan="2"><strong>Method</strong></th>
      <th colspan="3"><strong>Dirichlet</strong></th>
      <th colspan="2"><strong>Pathological</strong></th>
      <th rowspan="2"><strong>IID</strong></th>
    </tr>
    <tr>
      <th><strong>α=0.1</strong></th>
      <th><strong>α=0.5</strong></th>
      <th><strong>α=1</strong></th>
      <th><strong>2</strong></th>
      <th><strong>5</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>FedAvg</strong></td>
      <td align="center">56.3±0.71</td>
      <td align="center">62.0±0.79</td>
      <td align="center">63.2±0.76</td>
      <td align="center">53.7±0.45</td>
      <td align="center">60.1±0.44</td>
      <td align="center">65.0±0.25</td>
    </tr>
    <tr>
      <td><strong>FedProx</strong></td>
      <td align="center">55.3±0.73</td>
      <td align="center">62.8±0.69</td>
      <td align="center">63.7±0.67</td>
      <td align="center">53.0±0.59</td>
      <td align="center">61.6±0.52</td>
      <td align="center">63.1±0.39</td>
    </tr>
    <tr>
      <td><strong>FedAdam</strong></td>
      <td align="center">55.7±0.87</td>
      <td align="center">63.9±0.20</td>
      <td align="center">61.0±0.29</td>
      <td align="center">43.9±2.50</td>
      <td align="center">62.3±0.48</td>
      <td align="center">61.9±1.39</td>
    </tr>
    <tr>
      <td><strong>FedAvgM</strong></td>
      <td align="center">55.6±0.95</td>
      <td align="center">61.4±0.63</td>
      <td align="center">63.5±0.70</td>
      <td align="center">53.0±0.53</td>
      <td align="center">60.7±0.57</td>
      <td align="center">65.8±0.43</td>
    </tr>
    <tr>
      <td><strong>LocalNewton</strong></td>
      <td align="center">50.9±0.91</td>
      <td align="center">61.3±0.94</td>
      <td align="center">62.1±0.79</td>
      <td align="center">49.2±0.71</td>
      <td align="center">59.8±0.66</td>
      <td align="center">62.6±0.76</td>
    </tr>
    <tr>
      <td><strong>FedPM</strong></td>
      <td align="center">54.7±1.15</td>
      <td align="center">60.2±0.72</td>
      <td align="center">62.0±0.82</td>
      <td align="center">51.8±0.66</td>
      <td align="center">60.3±0.71</td>
      <td align="center">63.5±0.49</td>
    </tr>
    <tr>
      <td><strong>FedRCO-ori</strong></td>
      <td align="center">69.5±0.75</td>
      <td align="center">71.3±0.57</td>
      <td align="center">72.7±0.44</td>
      <td align="center">61.2±0.86</td>
      <td align="center">71.2±0.37</td>
      <td align="center"><strong>72.5±0.28</strong></td>
    </tr>
    <tr>
      <td><strong>FedRCO</strong></td>
      <td align="center"><strong>78.8±0.91</strong></td>
      <td align="center"><strong>74.2±0.71</strong></td>
      <td align="center"><strong>73.0±0.53</strong></td>
      <td align="center"><strong>75.3±1.43</strong></td>
      <td align="center"><strong>75.1±0.82</strong></td>
      <td align="center">71.9±0.30</td>
    </tr>
  </tbody>
</table>

<br>
<p><em>Table 3: The experimental results on EMNIST under the Dirichlet-non, Pathological-non, and IID settings with client number 100, and the party ratio 0.8 (%).</em></p>

<table>
  <thead>
    <tr>
      <th rowspan="2"><strong>Method</strong></th>
      <th colspan="3"><strong>Dirichlet</strong></th>
      <th colspan="2"><strong>Pathological</strong></th>
      <th rowspan="2"><strong>IID</strong></th>
    </tr>
    <tr>
      <th><strong>α=0.1</strong></th>
      <th><strong>α=0.5</strong></th>
      <th><strong>α=1</strong></th>
      <th><strong>10</strong></th>
      <th><strong>30</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>FedAvg</strong></td>
      <td align="center">81.8±0.50</td>
      <td align="center">83.5±0.42</td>
      <td align="center">83.6±0.42</td>
      <td align="center">80.9±0.50</td>
      <td align="center">82.6±0.45</td>
      <td align="center">83.8±0.39</td>
    </tr>
    <tr>
      <td><strong>FedProx</strong></td>
      <td align="center">81.7±0.51</td>
      <td align="center">83.1±0.46</td>
      <td align="center">83.3±0.43</td>
      <td align="center">80.1±0.50</td>
      <td align="center">82.2±0.50</td>
      <td align="center">83.9±0.37</td>
    </tr>
    <tr>
      <td><strong>FedAdam</strong></td>
      <td align="center">84.5±0.33</td>
      <td align="center">85.6±0.09</td>
      <td align="center">85.9±0.11</td>
      <td align="center">80.4±0.35</td>
      <td align="center">83.7±0.17</td>
      <td align="center">86.4±0.13</td>
    </tr>
    <tr>
      <td><strong>FedAvgM</strong></td>
      <td align="center">81.4±0.53</td>
      <td align="center">83.2±0.49</td>
      <td align="center">83.2±0.44</td>
      <td align="center">80.0±0.54</td>
      <td align="center">82.3±0.55</td>
      <td align="center">83.6±0.44</td>
    </tr>
    <tr>
      <td><strong>LocalNewton</strong></td>
      <td align="center">80.4±0.75</td>
      <td align="center">81.8±0.78</td>
      <td align="center">81.7±0.80</td>
      <td align="center">80.0±1.01</td>
      <td align="center">80.9±1.12</td>
      <td align="center">81.9±0.85</td>
    </tr>
    <tr>
      <td><strong>FedPM</strong></td>
      <td align="center">80.5±0.63</td>
      <td align="center">81.6±0.87</td>
      <td align="center">82.0±0.80</td>
      <td align="center">79.4±1.05</td>
      <td align="center">81.4±0.96</td>
      <td align="center">81.6±0.93</td>
    </tr>
    <tr>
      <td><strong>FedRCO-ori</strong></td>
      <td align="center">85.4±0.43</td>
      <td align="center">86.9±0.37</td>
      <td align="center">87.1±0.26</td>
      <td align="center">85.1±0.34</td>
      <td align="center">85.9±0.10</td>
      <td align="center"><strong>87.1±0.16</strong></td>
    </tr>
    <tr>
      <td><strong>FedRCO</strong></td>
      <td align="center"><strong>90.2±0.53</strong></td>
      <td align="center"><strong>88.6±0.40</strong></td>
      <td align="center"><strong>88.1±0.37</strong></td>
      <td align="center"><strong>88.2±1.11</strong></td>
      <td align="center"><strong>89.0±0.34</strong></td>
      <td align="center">87.0±0.18</td>
    </tr>
  </tbody>
</table>
<br>

<br>
<p><em>Table 4: The ablation experimental results of CIFAR-10 about client number and participation ratio on the Dirichlet distribution with Dir(α)=0.1 (%). For the client number part, the party ratio is set as 0.8, and for the party ratio part, the client number is set as 100.</em></p>

<table>
  <thead>
    <tr>
      <th rowspan="2"><strong>Method</strong></th>
      <th colspan="3"><strong>Client Number</strong></th>
      <th colspan="3"><strong>Party Ratio</strong></th>
    </tr>
    <tr>
      <th><strong>10</strong></th>
      <th><strong>50</strong></th>
      <th><strong>100</strong></th>
      <th><strong>0.1</strong></th>
      <th><strong>0.5</strong></th>
      <th><strong>1</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>FedAvg</strong></td>
      <td align="center">53.9±2.20</td>
      <td align="center">52.1±0.88</td>
      <td align="center">56.3±0.71</td>
      <td align="center">53.8±1.73</td>
      <td align="center">57.6±1.01</td>
      <td align="center">56.5±0.33</td>
    </tr>
    <tr>
      <td><strong>FedProx</strong></td>
      <td align="center">55.7±1.83</td>
      <td align="center">57.3±0.95</td>
      <td align="center">55.3±0.73</td>
      <td align="center">54.0±2.06</td>
      <td align="center">57.5±1.22</td>
      <td align="center">55.4±0.36</td>
    </tr>
    <tr>
      <td><strong>FedAdam</strong></td>
      <td align="center">45.6±1.60</td>
      <td align="center">53.9±0.74</td>
      <td align="center">55.7±0.87</td>
      <td align="center">39.7±2.85</td>
      <td align="center">54.9±1.94</td>
      <td align="center">52.5±0.51</td>
    </tr>
    <tr>
      <td><strong>FedAvgM</strong></td>
      <td align="center">51.7±1.15</td>
      <td align="center">57.0±1.09</td>
      <td align="center">55.6±0.95</td>
      <td align="center">55.5±0.83</td>
      <td align="center">55.9±0.83</td>
      <td align="center">55.1±0.44</td>
    </tr>
    <tr>
      <td><strong>LocalNewton</strong></td>
      <td align="center">49.5±2.13</td>
      <td align="center">55.9±2.06</td>
      <td align="center">50.9±0.91</td>
      <td align="center">51.2±2.86</td>
      <td align="center">53.4±1.43</td>
      <td align="center">53.8±0.62</td>
    </tr>
    <tr>
      <td><strong>FedPM</strong></td>
      <td align="center">53.9±1.91</td>
      <td align="center">50.7±1.34</td>
      <td align="center">54.7±1.15</td>
      <td align="center">54.6±2.88</td>
      <td align="center">55.1±1.72</td>
      <td align="center">54.3±0.69</td>
    </tr>
    <tr>
      <td><strong>FedRCO-ori</strong></td>
      <td align="center">62.2±0.56</td>
      <td align="center">60.9±0.85</td>
      <td align="center">69.5±0.75</td>
      <td align="center"><strong>65.0±2.83</strong></td>
      <td align="center">67.5±0.72</td>
      <td align="center">66.2±0.45</td>
    </tr>
    <tr>
      <td><strong>FedRCO</strong></td>
      <td align="center"><strong>74.3±1.13</strong></td>
      <td align="center"><strong>78.6±1.12</strong></td>
      <td align="center"><strong>78.8±0.91</strong></td>
      <td align="center">63.0±1.82</td>
      <td align="center"><strong>73.7±1.08</strong></td>
      <td align="center"><strong>76.4±0.79</strong></td>
    </tr>
  </tbody>
</table>
<br>

<br>
<p><em>Table 5: The ablation experimental results of EMNIST about client number and participation ratio on the Dirichlet distribution with Dir(α)=0.1 (%). For the client number part, the party ratio is set as 0.8, and for the party ratio part, the client number is set as 100.</em></p>

<table>
  <thead>
    <tr>
      <th rowspan="2"><strong>Method</strong></th>
      <th colspan="3"><strong>Client Number</strong></th>
      <th colspan="3"><strong>Party Ratio</strong></th>
    </tr>
    <tr>
      <th><strong>10</strong></th>
      <th><strong>50</strong></th>
      <th><strong>100</strong></th>
      <th><strong>0.1</strong></th>
      <th><strong>0.5</strong></th>
      <th><strong>1</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>FedAvg</strong></td>
      <td align="center">77.9±0.75</td>
      <td align="center">81.4±0.28</td>
      <td align="center">81.8±0.50</td>
      <td align="center">80.6±1.38</td>
      <td align="center">81.4±0.31</td>
      <td align="center">81.5±0.18</td>
    </tr>
    <tr>
      <td><strong>FedProx</strong></td>
      <td align="center">78.1±1.03</td>
      <td align="center">81.0±0.34</td>
      <td align="center">81.7±0.51</td>
      <td align="center">80.7±1.24</td>
      <td align="center">81.9±0.25</td>
      <td align="center">81.5±0.18</td>
    </tr>
    <tr>
      <td><strong>FedAdam</strong></td>
      <td align="center">79.5±0.56</td>
      <td align="center">83.4±0.52</td>
      <td align="center">84.5±0.33</td>
      <td align="center">84.0±1.80</td>
      <td align="center">84.7±0.54</td>
      <td align="center">84.6±0.22</td>
    </tr>
    <tr>
      <td><strong>FedAvgM</strong></td>
      <td align="center">78.1±0.46</td>
      <td align="center">81.6±0.18</td>
      <td align="center">81.4±0.53</td>
      <td align="center">81.1±0.99</td>
      <td align="center">81.9±0.33</td>
      <td align="center">81.2±0.17</td>
    </tr>
    <tr>
      <td><strong>LocalNewton</strong></td>
      <td align="center">75.8±0.13</td>
      <td align="center">79.1±0.28</td>
      <td align="center">80.4±0.75</td>
      <td align="center">79.8±0.99</td>
      <td align="center">80.6±0.21</td>
      <td align="center">80.2±0.11</td>
    </tr>
    <tr>
      <td><strong>FedPM</strong></td>
      <td align="center">76.0±0.33</td>
      <td align="center">79.5±0.12</td>
      <td align="center">80.5±0.63</td>
      <td align="center">80.2±1.20</td>
      <td align="center">79.9±0.24</td>
      <td align="center">80.4±0.26</td>
    </tr>
    <tr>
      <td><strong>FedRCO-ori</strong></td>
      <td align="center">80.5±0.39</td>
      <td align="center">83.9±0.72</td>
      <td align="center">85.4±0.43</td>
      <td align="center">85.3±1.51</td>
      <td align="center">85.3±0.56</td>
      <td align="center">85.3±0.37</td>
    </tr>
    <tr>
      <td><strong>FedRCO</strong></td>
      <td align="center"><strong>88.5±0.86</strong></td>
      <td align="center"><strong>90.8±0.87</strong></td>
      <td align="center"><strong>90.2±0.53</strong></td>
      <td align="center"><strong>85.6±1.46</strong></td>
      <td align="center"><strong>88.7±0.50</strong></td>
      <td align="center"><strong>91.0±0.37</strong></td>
    </tr>
  </tbody>
</table>
<br>
<br><br>


<p><em>Table 6: Summary of theoretical convergence rates. Here, T is the total communication rounds, K is local epochs, C is total clients, and $\kappa$ represents the condition number of the local Hessian/preconditioner.</em></p>



| **Algorithm** | **Order** | **Convergence Rate (Non-convex)** | **Bottleneck / Assumption in non-IID** |
| :--- | :---: | :---: | :--- |
| **FedAvg** | 1st | $\mathcal{O}\left( \frac{1}{\sqrt{C K T}} + \frac{\sigma^2}{E} \right)$ | Severely penalized by the massive client drift term ($\sigma^2$). |
| **FedAvgM** | 1st | $\mathcal{O}\left( \frac{1}{\sqrt{C K T}} + \frac{\sigma^2}{E} \right)$ | Momentum smooths trajectory empirically but retains the drift penalty. |
| **FedProx** | 1st | $\mathcal{O}\left( \frac{1}{\sqrt{C K T}} + \mathcal{O}(\mu) \right)$ | Proximal term $\mu$ restricts drift but forces prohibitively slow convergence. |
| **FedAdam** | 1st | $\mathcal{O}\left( \frac{1}{\sqrt{C K T}} + \text{Drift} \right)$ | Server-side adaptivity fails to correct local curvature distortions. |
| **SCAFFOLD** | 1st | $\mathcal{O}\left( \frac{1}{\sqrt{C K T}} \right)$ | Control variates critically lag or diverge in extreme label skew. |
| **LocalNewton** | 2nd | $\mathcal{O}\left( \frac{\kappa^2}{T} \right)$ or **Diverges** | Catastrophically diverges as condition number $\kappa \to \infty$ under skew. |
| **FedPM** | 2nd | Superlinear | Proof strictly restricted to **Strongly Convex** and $K=1$. |
| **FedRCO (Ours)** | **2nd** | **$\mathcal{O}\left( \frac{1}{T} \right)$** | **Strictly bounds $\kappa \le \kappa_{\max}$**, ensuring non-convex stability for $K>1$. |

