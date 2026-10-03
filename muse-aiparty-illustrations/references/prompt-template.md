# 生图提示词模板（小派甜美精致版）

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

CHARACTER LOCK 块每次原样复用，一字不改。管线支持参考图时，务必附上 `references/character/` 的两张基准图。

```text
Generate one standalone 16:9 horizontal Chinese article illustration, sweet refined doll-photography style.

CHARACTER LOCK (reuse verbatim, do not alter):
Pai, a sweet doll girl IP character: round face, big brown eyes, blush and freckles, small blue and pink star stickers on cheeks; extremely long straight light-blonde hair with center parting; left-side hair accessory cluster: big silver star clip, pink bow, small blue clips, white bunny charm, pink stars and dangling small stars; thin silver necklace with blue star pendant; pink ribbed lace camisole with small bow; off-white high-waist shorts; white chunky knit leg warmers with yellow star embroidery; cream platform Mary Jane shoes; doll proportions, big head, slender limbs; gentle sweet expression.

Visual DNA:
Soft studio lighting, clean pastel background (light pink, cream, or mist blue), refined polished finish, generous negative space. Sparse short handwritten-style Chinese annotations in soft colors. Sweet, polished and clean, with a charming absurd contrast: a delicate doll seriously performing a strange-but-logical task. No PPT infographic look, no formal flowchart, no dark or horror mood, no cluttered background, no photorealistic UI screenshots.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小派在哪里、正在做什么、主要物件是什么、信息如何流动。善用"小个子娃娃 vs 巨型物件"的体型反差制造记忆点}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese labels (short, soft handwritten style):
{标注词1} / {标注词2} / {标注词3} / {标注词4}

Color use:
Pink, white and cream base matching Pai's outfit; star yellow and mist blue accents. Soft red for key warnings/results, apricot orange for main flow/paths, mist blue for secondary notes. Pastel background in light pink, cream, or mist blue chosen to fit the article's mood.

Constraints:
One image explains only one core structure. Pai must perform the core conceptual action, not decorate the scene. Keep the main subject around 40%-60% of the canvas with at least 35% quiet negative space. At most 5-8 short Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not copy prior examples; invent a fresh visual metaphor for this specific article. Never alter Pai's locked features: face, hair color and style, left-side accessory cluster, star stickers, outfit pieces.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the text "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean pastel background, matching the surroundings. Preserve everything else exactly: character, labels, paths, composition, aspect ratio, and image quality. Do not add any new text or objects. Do not alter Pai's face, hair, or outfit.
```

修正形象走样：

```text
Edit the provided image. Fix only this character issue: {具体走样项，如左侧发饰缺失 / 瞳色不对 / 发型走样}, making Pai match the reference images. Preserve everything else exactly: composition, background, labels, aspect ratio, and image quality. Do not add new text or objects.
```

增强小派参与感：

```text
Regenerate this illustration with the same core meaning and soft sweet style, but make Pai the true performer of the conceptual action. She should be doing the strange work that explains the idea with her own hands, not standing beside the scene. Keep it sweet, polished, clean, with generous negative space. Reuse the CHARACTER LOCK verbatim.
```
