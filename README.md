# 使用方式


```
podman build -t  local/demo-web
podman run -p 8080:80 local/demo-web
```

JS

```
const products = [
    {
        id: '1',
        title: '產品一',
        price: 10,
        img: 'https://picsum.photos/id/999/1200/600',
        tags: ['生活用品', '工具'],
        isAvailable: true
    },
    {
        id: '2',
        title: '產品二',
        price: 60,
        img: 'https://picsum.photos/id/1070/1200/600',
        tags: ['藥妝'],
        isAvailable: true
    },
    ....
    // 以此類推
];
```

圖片都是透過 https://picsum.photos  上產生假圖 ....


## DEMO


![](https://hackmd.io/_uploads/S1a6CRmj3.png)

![](https://hackmd.io/_uploads/Skt1y1Nsh.png)