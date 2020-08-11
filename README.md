# costruct2
엇 저는 패킷 로스 실습시 저는 명령어를 아래처럼 변경하니까 실행이 됩니다.
sudo tc qdisc add dev lo root netem loss 10%  
sudo tc qdisc change dev lo root netem loss 10%
