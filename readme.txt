git��ʹ������

1.��д�û���Ϣ
git config  --global user.name "jiangchao"
git config  --global user.name "414345390@qq.com"

2.�����汾��
���磺��Ҫ��ŵİ汾�����ڵ�λ�ã�
d/testgit
cd d          ����d��

mkdir testgit ---- �����ļ�Ŀ¼

pwd ---�鿴�ļ�Ŀ¼·��

3.ͨ������ git init �����Ŀ¼���git���Թ���Ĳֿ�
git init 

4.���ļ���ӵ��汾����
  <1> git add readme.txt --��ӵ��ݴ�������ȥ
  <2> git commit -m "readme.txt �ύ"---���ύ��ע�� 
  <3> git status ----ͨ������git status���鿴�Ƿ����ļ�δ�ύ	
  <4> git diff readme.txt ---�鿴�ļ�����ʲô���ݡ�

5.�汾����
<1> git log(git log �Cpretty=oneline) ---��ʾ���������Զ����ʾ��־	
<2> git reset  --hard HEAD^ ---���˵���һ�汾
<3> git reset  --hard HEAD^^ ---���˵����ϸ��汾
<4> git reset  --hard HEAD~100  ---���˵���100���汾
<5> git reset  --hard ---�汾��
<6> git reflog  ----�鿴�޸����ݵİ汾��
<7> git reset  --hard 6fcfc89 ---���˵�ָ���İ汾��


6.Git�����޸ĺ�ɾ���ļ�������
<1> git checkout  -- readme.txt(�ļ���)  ---����readme.txt�ļ��ڹ����������޸�ȫ������