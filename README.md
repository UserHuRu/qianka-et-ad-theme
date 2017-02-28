# qianka-et-ad-theme
> element component theme for qianka platform.


## Installation
```shell
npm i qianka-et-ad-theme -S
```

## Usage

Use Sass Or postcss-import
```css
@import 'qianka-et-ad-theme';
```

Or Use webpack
```javascript
import 'qianka-et-ad-theme';
```

Or
```html
<link rel="stylesheet" href="path/to/node_modules/qianka-et-ad-theme/lib/index.css">
```

##  Import your need
```javascript
import 'qianka-et-ad-theme/lib/input.css';
import 'qianka-et-ad-theme/lib/select.css';
���deploy�е�����
// ...
```

## Build

```shell
gulp build
```

ִ��build�Ժ󣬻���libĿ¼�����ɱ������ļ�

### Deploy with files

����libĿ¼�µ�index.css�������ļ�Ŀ¼fonts

## ���

### Dialog �Ի���

<table>
        <tr>
            <th>����</th>
            <th>˵��</th>
            <th>��ѡֵ</th>
            <th>qt��������ֵ</th>
        </tr>
        <tr>
            <td>size</td>
            <td>Dialog �Ĵ�С</td>
            <td>tiny/small/large/full</td>
            <td>fixed390</td>
        </tr>
        <tr>
            <td>˵��</td>
            <td></td>
            <td>  tiny 30%;
                  small: 50%;
                  large: 90%;
                  full����������Ļ</td>
            <td>
                ��ȹ̶�Ϊ390px
            </td>
        </tr>
    </table>

   ԭel���ֻ��֧�ֿ����������
   ```
  <el-dialog title="ɾ��" v-model="dialogVisible" size="tiny" top="38%">
        ...
  </el-dialog>
   ```
   qk����Ĺ̶�����390px��ʹ��
   ```
    <el-dialog title="ɾ��" v-model="dialogVisible" size="fixed390" top="38%">
        ...
  </el-dialog>
   ```

   ���ڶԻ���߶ȡ���С����߱ȵ���֪���⣺

   Ҫ�󣺶Ի����ȹ̶�Ϊ390px���߶ȹ̶�Ϊ202px�����߱����ڽӽ�����Ӿ��Ŀ�߱ȡ�

   dialog�Ի�������Ŀ�Ⱥ͸߶����޷�ͬʱ����Ϊһ���̶�ֵ�ģ���Ϊdialog�ĶԻ���ʵ�ʵĴ�С��body�������ݾ���,�Ի�������߶� = ͷ���߶�+���ݸ߶�+��ע�߶�+��Χ�߾ࡣ����Ŀǰfixed390�Ի���ĸ߶�202px���ɽ�ע�߶ȶ����߾���25px����Ϊ12px��ƴ�ճ����ġ�������������ж����������ݣ�������һ�����ݣ��������Ի���߶���Ȼ����������ô�Ǹ�ʱ�����ڸ߶ȹ̶�Ϊ390px����������ӣ����Ϳ�ı����ֻᷢ���仯�����ԣ��ع�ͷ��������Ʒ����ô����������أ�

   ����el���е����ģʽ��ֱ��������������Ի������ͻ������ӣ����������ӱ������趨�ĶԻ���������30%��50%��90%�����Ӽ�����������Ӧ����

### Button ��ť
