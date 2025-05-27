使用Tailwind CSS制作Javascript网页，Dark theme。

网页标题：Packaging Printing Document Generator

结构如下：

File name [input area]
File type A B C D K 这个做选择，不需要输出

if file type is A

Dimension [input L] x [input W] x [input H]
按照顺序输入 L x W x H

Color default Monochrome

Material Option
- None
- H737H
- D525D
- K=K
- K3K

if file type is B

Dimension [L]x[W]x[H] 我需要3个inline input输入 L W H

Color option
- CMYK
- CMYK + Pantone （output 为CMYK + Pantone 2587 C (Purple) + Pantone 368 C (Green)）
- Monochrome
- N/A

Material Option
- None
- Art Card 400gsm
- Art Card 350gsm
- Art Card 350gsm + F-flute
- Other (input text for this option)

Finishing Option
- None
- Matte Lamination

Product image with UV Option
- No
- Yes

Sealer
- 3pcs
- 4pcs
- 5pcs
- 6pcs

If file type is C
Dimension [input L] x [input W] x [input H]
按照顺序输入 L x W x H
如果只输入了 W和H，output为 W x H，L就忽略掉。

Color option
- None
- CMYK
- CMYK + Pantone （output 为CMYK + Pantone 2587 C (Purple) + Pantone 368 C (Green)）
- Monochrome

Material Option
- None
- Art Card 400gsm
- Art Card 350gsm
- F-flute
- E-flute
- Pulp Tray
- Blister
- EVA
- PE
- Other (input text for this option)

Finishing Option
- None
- Matte Lamination

If file type is D

Color option
- None
- CMYK
- Monochrome

Material Option
- None
- Art Paper 128gsm
- Art Paper 157gsm
- Book Paper 80gsm
- Other (input text for this option)

If file type is K
Material Option
- None
- Woodfree Label
- Mirrokote Label
- Other (input text for this option)

输出的文字Format

File：insta 20_box_CC_5312
Dimension： 138 x 66 x 173 mm
Color: CMYK + Pantone 2587 C (Purple) + Pantone 368 C (Green)）
Material：Art Card 350gsm
Finishing: Matter Lamination
UV: Product image with UV
Sealer：30mm x 3pcs

以上选项做好选择后，点击Preview 按钮，在下方生成文字内容。文字内容有一copy button

测试结果

File：B_3dPen_Make_Box_Blue_5527
Dimension：160 x 53 x 173 mm
Color: CMYK + Pantone 2587 C (Purple) + Pantone 368 C (Green)
Material：Art Card 350gsm + F-flute
Finishing: Matte Lamination
UV: Product image with UV
Sealer：30mm x 3pcs

双语输出结果

File: file name
Dimension: 111 x 112 x 31 mm
Color: CMYK + Pantone 2587 C (Purple) + Pantone 368 C (Green)
Material: Art Card 400gsm
Finishing: Matte Lamination
UV: Product image with UV
Sealer: 30mm x 3pcs

文件：file name
尺寸：111 x 112 x 31 mm
颜色：四色加潘通色（Pantone 2587 C（紫）+ Pantone 368 C（绿））
材质：Art Card 400gsm
表面处理：哑膜
UV：产品图UV处理
封口：30mm x 3pcs