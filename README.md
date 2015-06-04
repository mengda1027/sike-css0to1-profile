# CSS��ϰ


----------


## D1
- ������ normalize.css
- ��װ BrowserSync
- ��margin�������ʱ��ֹ���������������۵���ࣩ���ڸ������padding:1px; [�ο���Collapsing Margins][1]

## D2
- ��ռ�ĵ�����Ԫ��
  1. fixed����absolute��λ��Ԫ��
  2. Ʈ��Ԫ��CSS
  3. ����ͼ
- ����α�����������clearfix��ʽ���Լ�overflow:hidden�����ԭ��[CSS2.1 10.6.7 �㷨][2]
- html���廯��Semantic Elements��
 + ����ģ��Ӧ��ʹ�� nav
 + ����ģ���Ӧ��ʹ�� article
 + ͷ��ģ��Ӧ��ʹ�� header

## D3
- float���ֱ������ݰ�ΧƮ��Ԫ��:��������������Ϊoverflow:hidden������������Ϊbfc.[How does the CSS Block Formatting Context work][3]
- ����border-box�޸�Ĭ�ϵ�content-box����[IE8+֧��][4]

## D4
- ���Զ�λ��absolute���ĵ������������ǣ�
 1. ��һ����Ҫ��������ļ��������������֣�
 2. ��������һ��������� (����С���)��
 3. ������������λ���������Ҫ�����λ�á�
- ע�⣺������Ҫָ��relative,���Զ�λ���Ҫָ�����

  [1]: http://www.sitepoint.com/web-foundations/collapsing-margins/
  [2]: http://www.w3.org/TR/2011/REC-CSS2-20110607/visudet.html#root-height
  [3]: http://stackoverflow.com/a/6199172
  [4]: http://caniuse.com/#search=box-sizing