1. ���ֱ�ӽ���Щ�ļ����ϴ���linux������(�����ϴ���~/jobs/oozie�ļ�����)��Ȼ����������ϴ���hdfs��/oozie/workflows�ļ����С�����linux�ϴ���Ŀ¼(������jobs/oozie�ļ���)ִ��oozie job -oozie http://hh:11000/oozie -config ./xxxx/job.properties -run�������xxxx���Ǹ����ļ������ơ�
2. �������
oozie job -oozie http://hh:11000/oozie -config ./xxxx/job.properties -submit ���ύ����
oozie job -oozie http://hh:11000/oozie -start job_id (�����Ѿ��ύ������)
oozie job -oozie http://hh:11000/oozie -config ./xxxx/job.properties -run (submit��start����ϲ�)
oozie job -oozie http://hh:11000/oozie -info job_id (��ȡ������Ϣ)
oozie job -oozie http://hh:11000/oozie -suspend job_id (��ͣ/��������)
oozie job -oozie http://hh:11000/oozie -rerun job_id (����������ͣ������)