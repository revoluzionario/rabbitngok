# How to create a new post

### 1. Create a new file in the `posts` directory. The file name in the format `your-title.mdx`. For example, `tin-chuan-chua-anh.mdx`.

### 2. Add the following content to the file:

```mdx
---
title: Your title
description: Your description
mainImage: Image URL
categories: ["category1", "category2"]
createdAt: 1665810787689 // get the current timestamp from https://currentmillis.com/
---

## Section 1

Your content

## Section 2

Your content

[...]
```

### 3. Replace the `title`, `description`, `mainImage`, `categories` and `createdAt` with your own content.

## Example

```mdx
---
title: Tin chuẩn chưa anh?
description: Đây là câu nói nổi tiếng nhất khi nói về BLV Anh Ngok.
mainImage: http://mewcloud.up.railway.app/file/afd5b4ac8314dde3b12e36ed309f4e57/tin-chuan-chua-anh.jpg
categories: ["Comment"]
createdAt: 1665801957056
---

## Tin chuẩn chưa anh?

[![tin-chuan-chua-anh](http://mewcloud.up.railway.app/file/afd5b4ac8314dde3b12e36ed309f4e57/tin-chuan-chua-anh.jpg)](/post/tin-chuan-chua-anh)

Đây là câu nói nổi tiếng nhất khi nói về BLV Anh Ngok, bắt nguồn từ legend Trịnh Quang Tuyến. Và câu nói rep lại của Ngok cũng nổi tiếng không kém: "Chuẩn em nhé".

Câu nói này được sử dụng rộng rãi nhất trên cả nước, trong nhiều TH, nhất là những bài đăng của các nhà báo, nhà đài về một thông tin nào đó.

```

## Special Notes

- The `createdAt` is the timestamp of the post. It is used to sort the posts by the latest post first.
  - The timestamp is in milliseconds. You can get the current timestamp from [currentmillis.com](https://currentmillis.com/).

- The `categories` is an array of categories. You can add multiple categories to a post.

- The `mainImage` is the image of the post. It is used in the post list page and the post detail page. You can just use the image uploaded from [here](https://mewcloud.up.railway.app/) or it is placed in the `assets` folder.
  - Example: 
    - From MewCloud: `http://mewcloud.up.railway.app/file/afd5b4ac8314dde3b12e36ed309f4e57/tin-chuan-chua-anh.jpg`
    - From assets folder: `https://raw.githubusercontent.com/<your-username>/<your-repo>/main/assets/tin-chuan-chua-anh/main-image.jpg`

- The `description` is the description of the post. It is used in the post list page and the post detail page.

- The `title` is the title of the post. It is used in the post list page and the post detail page.

- You need learn the syntax of [`Markdown`](https://www.markdownguide.org/basic-syntax/) to write the content of the post.