# SFEBarrier


```yaml
Name of Quantlet: SFEBarrier

Published in:     Statistics of Financial Markets I

Description:      'Compare and plots two possible paths of the asset price. Once the asset price hits the 
                  barrier, the option expires worthless or becomes activated (depending upon the type of 
                  barrier option), regardless of future stock price.'

Keywords:         exotic-option, asset, stochastic-process, time-series, plot

See also:         SFEdown-and-out

Author:           Chinghsi Lee, Sai Niranjan Mohanamurali

Submitted:        2015/12/30

Input:            - S0 : Stock's Initial Price 
                  - r : Interest Rate per year 
                  - vol : Volatility per year 
                  - b : Barrier 
                  - c : Type of Barrier Option (1: Down and Out, 2: Up and Out, 3: Down and In, 4: Up and In)
                  
                  'User inputs the SFEBarrier parameters [Stock\'s Initial Price, Interest Rate, Volatility, 
                  Barrier, Type of Barrier option] like [200, 0.05, 0.03, 100, 1]'

Output:           Plot of a Barrier Option, depending on the type chosen

Example:          '- 1: Down and Out Option: [200, 0.05, 0.03, 100, 1]'
                  '- 2: Up and Out Option:   [200, 0.05, 0.03, 300, 2]'
                  '- 3: Down and In Option:  [200, 0.05, 0.03, 125, 3]'
                  '- 4: Up and In Option:    [200, 0.05, 0.03, 275, 4]'


```

##Down and Out Option 


![alt tag](https://cloud.githubusercontent.com/assets/15204857/12089267/5a133814-b2e3-11e5-8d23-34d4f3989c99.png "Down and Out Option")

##Up and Out Option 


![alt tag](https://cloud.githubusercontent.com/assets/15204857/12089278/6fde4120-b2e3-11e5-8e13-837222e410f8.png "Up and Out Option")

##Down and In Option


![alt tag](https://cloud.githubusercontent.com/assets/15204857/12089244/28fdea62-b2e3-11e5-928f-61fe11406110.png "Down and In Option")

##Up and In Option


![alt tag](https://cloud.githubusercontent.com/assets/15204857/12089256/44835402-b2e3-11e5-8c11-9a856a8424db.png "Up and In Option")


```r

```
