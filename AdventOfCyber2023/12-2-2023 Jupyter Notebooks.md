<h3> Jupyter Notebooks </h3>
<b>Question:</b>
-How many packets were captured? Answer: 100
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('network_traffic.csv')
df.head(5)
df.count()
```
![[Pasted image 20231202113429.png]]

-What IP address sent the most amount of traffic during the packet capture? Answer: 10.10.1.4
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('network_traffic.csv')
df.head(5)
df.count()
df.groupby(['Source']).size()
```
![[Pasted image 20231202113914.png]]


-What was the most frequent protocol? Answer: ICMP
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('network_traffic.csv')
df.head(5)
df.count()
#df.groupby(['Source']).size()
df.groupby(['Protocol']).size()
```
![[Pasted image 20231202114038.png]]

