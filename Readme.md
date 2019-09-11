
Install virtualenv
```
sudo pip install virtualenv 
```

Create and activate virtual environment
```
virtualenv venv -p python3.5
source venv/bin/activate
```

install pytorch with no cuda
```bash
check here: https://pytorch.org/
pip3 install torch==1.2.0+cpu torchvision==0.4.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
```

Install all dependencies
```
pip install -r requirements.txt
```


Assignment submission
```
# zip the assignment submission folder
cd assignment_3
sh collect_submission.sh
cd ..
```
