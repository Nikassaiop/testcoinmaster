###������ Testnet
�������� ����-��� ���� ���������� �����, � ������� ������������ ����� ������ � ���� ����� ���� ��������� �� ������� ��� �� ��������� ����������. ��� �������, �� �� ������ ������������� �������, ������� ����� ��������� ��� ������ ���������������� ���� ��� ����������������� ����.

������ ����� ��� ������� ��������� Daemon � �����������:
```
--testnet � --data-dir
```
��� �������� ��������� Daemon � ������� �������� ����, � ����� ������� ����� ����� ��� ���������� ������ ��������� ����.

��������:

```
testcoined --testnet --data-dir=new / path/to / blockchain
```
###����������� ��������
����������� ��������� ����� ������. ���������� �������� ��������� 
```
--testnet
```
�������:
```
simplewallet --testnet
```
###����������� � �������� ���� �������������� �����
��� ������ Testnet ���������� � ���������� ������� ������ ����. ��� �� �����, ������� ����������� ���������� �������������� ����:
```
cryptonotecoind --testnet --data-dir=new / path/to / blockchain --add-exclusive-node=testnet.node.IP.port
```