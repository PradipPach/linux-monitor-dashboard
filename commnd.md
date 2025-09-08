sudo yum install python3 -y
sudo yum install python3-tkinter
sudo yum  install pip -y
sudo yum install git -y
git config --global user.name "pradip pachapol"
git config --global user.email "pachapolp2932002@gmail.com"
git clone https://github.com/PradipPach/linux-monitor-dashboard.git
cd linux-monitor-dashboard
pip3 install flask
pip install -r requirements.txt
python3 web_ui.py
