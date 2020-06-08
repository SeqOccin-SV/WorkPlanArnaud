
### Genotyping variants using svviz

https://github.com/nspies/svviz2

### environment
```
module load system/Python-3.6.3
module load bioinfo/trf-v4.09
python3 -m venv svvizenv
source svvizenv/bin/activate
pip install rpy2
pip install -U git+git://github.com/nspies/svviz2.git
