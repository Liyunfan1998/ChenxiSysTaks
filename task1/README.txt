TASK1�� �ı�����

���������ʹ�� python3 ��ɡ�����ļ���files�ļ��С�
1���� new.txt �������Ϣ��ͨ�� labels.txt �� lables_id תΪ lables_name������ old.json �����Ӧjson������ fileid �� senid ȷ��Ψһ�ԣ����½���5����ֵ�� newmentions����ͬ��mentions ��ֵ�ԡ���һ��д�� new.json �ļ�
2������ new.json չʾÿһ��json���� mentions �� newmentions ֮��Ĳ��졣д�� diff.txt �ļ�����ʽ���⣬����ʹ������ diff �ĸ�ʽ�������

files�ļ������ļ���ʽ˵����
old.json��ʽ��
{	"tokens": 
		["John", "R.", "Wilke", "contribued", "to", "this", "article", "."], 
	"senid": 41, 
	"mentions": 
		[{"start": 0, "labels": ["/PERSON"], "end": 3}], 
	"fileid": "WSJ1829"
}
ÿ��һ��json����������4���ֵ�ԣ�fileid��senid��tokens��mentions������mentions��ֵ�����Ƕ��json������б�����һ���������start��labels(labels_name)��end��3����ֵ�ԡ�

new.txt��ʽ��
	WSJ1380_13_-1_-1	6,7
ÿ�ж�Ӧһ���²��Ե�mention��ǰ�벿�����»��߸������� fileid��senid��mention start��mention end����벿����mention labels_id

labels.txt��ʽ��
	/SUBSTANCE	13	5562
ÿ�ж�Ӧһ��labels�� labels_name, labels_id �� labels_count��3��ֵ����labels_count�ڱ�task��û��ʹ�ã�


