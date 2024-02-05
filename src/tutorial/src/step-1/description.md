# Başlarken {#getting-started}

Vue öğreticisine hoş geldiniz!

Bu öğreticinin amacı, Vue ile çalışmanın tarayıcıda nasıl hissettirdiğini size hızlı bir şekilde deneyimletmektir. Kapsamlı olmayı amaçlamaz ve ilerlemeden önce her şeyi anlamanız gerekmez. Ancak tamamladıktan sonra, her konuyu daha ayrıntılı bir şekilde ele alan <a target="_blank" href="/guide/introduction.html">Rehber</a>'i de okumayı unutmayın.

## Ön Koşullar {#prerequisites}

Bu öğretici, HTML, CSS ve JavaScript ile temel düzeyde bilgi sahibi olduğunuzu varsayar. Eğer tamamen yeni bir ön yüz geliştirmeye başlıyorsanız, ilk adımınız olarak doğrudan bir çerçeve kullanmak belki de en iyi fikir olmayabilir - önce temelleri kavrayın, ardından geri gelin! Diğer çerçevelerle önceki deneyim faydalı olabilir, ancak zorunlu değildir.

## Bu Öğreticiyi Nasıl Kullanmalısınız? {#how-to-use-this-tutorial}

Kodu sağdaki <span class="wide">alan</span><span class="narrow">altında</span> düzenleyebilir ve sonucun anında güncellendiğini görebilirsiniz. Her adım, Vue'un temel bir özelliğini tanıtacak ve demo'yu çalıştırmak için kodu tamamlamanız beklenir. Takılırsanız, size çalışan kodu ortaya çıkaran "Bana Göster!" düğmesine sahip olacaksınız. Ancak bunun üzerine fazla bel bağlamamaya çalışın - kendi başınıza çözümleyerek daha hızlı öğreneceksiniz.

Eğer Vue 2 veya diğer çerçevelerden geliyorsanız, bu öğreticiden en iyi şekilde yararlanmak için birkaç ayarı özelleştirebilirsiniz. Eğer bir başlangıç seviyesindeyseniz, varsayılanları kullanmanız önerilir.

<details>
<summary>Öğretici Ayarı Detayları</summary>

- Vue, Options -Seçenekler- API -Uygulama Programlama Arayüzü- ve Composition -Kompozisyon- API olmak üzere iki API stili sunar. Bu öğretici, her ikisiyle de çalışacak şekilde tasarlanmıştır - tercih ettiğiniz stili API Tercihi anahtarlarını kullanarak seçebilirsiniz. <a target="_blank" href="/guide/introduction.html#api-styles">API stilleri hakkında daha fazla bilgi edinin</a>.

- Ayrıca, SFC modu veya HTML modu arasında geçiş yapabilirsiniz. İlk seçenek, <a target="_blank" href="/guide/introduction.html#single-file-components">Tek Dosya Bileşeni</a> (SFC) biçiminde kod örneklerini gösterecek ve bu genellikle geliştiricilerin Vue'u bir derleme adımıyla kullandıkları formattır. HTML modu, derleme adımı olmadan kullanımı gösterir.

<div class="html">

:::tip
Eğer kendi uygulamalarınızda derleme adımı olmadan HTML modunu kullanacaksanız, içerikleri şu şekilde değiştirmeniz önemlidir:

```js
import { ... } from 'vue/dist/vue.esm-bundler.js'
```

komut dosyası içinde veya yapılandırma aracınızı `vue`'yi buna göre çözmesi için yapılandırın. [Vite](https://vitejs.dev/) için örnek yapılandırma:

```js
// vite.config.js
export default {
  resolve: {
    alias: {
      vue: 'vue/dist/vue.esm-bundler.js'
    }
  }
}
```

Daha fazla bilgi için ilgili [bölüme bakın](/guide/scaling-up/tooling.html#note-on-in-browser-template-compilation).
:::

</div>

</details>

Hazır mısınız? Başlamak için "İleri" düğmesine tıklayın.