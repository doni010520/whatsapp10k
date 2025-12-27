# ✅ CHECKLIST DE PERSONALIZAÇÃO

## Antes de colocar no ar, faça estas alterações:

---

## 🔗 1. LINK DE CHECKOUT (3 lugares)

Abra o arquivo `index.html` e busque por: `href="#checkout"`

**Há 3 ocorrências. Substitua TODAS por:**
```html
href="https://pay.kiwify.com.br/SEULINK"
```

### Como conseguir o link:
1. Crie conta na Kiwify: https://kiwify.com.br
2. Cadastre produto "WhatsApp 10K" por R$ 67
3. Copie o link de checkout
4. Cole no HTML

### Localizações aproximadas:
- Linha ~540 (botão no card preto)
- Linha ~560 (botão na seção de conteúdo)
- Linha ~650 (botão final)

---

## 📱 2. WHATSAPP DE CONTATO (1 lugar)

Busque por: `https://wa.me/5571999999999`

**Substitua por:**
```html
https://wa.me/55SEUDDD+SEUNUMERO
```

**Exemplo:**
```html
https://wa.me/5511987654321?text=Olá! Tenho interesse no WhatsApp 10K
```

### Formato:
- 55 = Código do Brasil
- 11 = DDD (sua cidade)
- 987654321 = Seu número (com 9 dígitos)

### Localização aproximada:
- Linha ~680 (botão flutuante do WhatsApp)

---

## 🏢 3. CNPJ/CPF (1 lugar)

Busque por: `CNPJ: XX.XXX.XXX/0001-XX`

**Substitua pelo seu:**
- CNPJ: `12.345.678/0001-90`
- OU CPF: `123.456.789-00`

### Localização aproximada:
- Linha ~670 (rodapé da página)

---

## 📧 4. NOME DO AUTOR (opcional)

Se não for "Adonias Santos", busque por: `Adonias Santos`

**Há várias ocorrências. Substitua pelo seu nome.**

Localizações:
- Linha ~540 (card preto)
- Linha ~610 (seção "Quem é")
- Linha ~665 (rodapé)

---

## 📅 5. TEXTO DA URGENCY BAR (opcional)

Busque por: `OFERTA ESPECIAL POR TEMPO LIMITADO`

**Você pode mudar para:**
- "PROMOÇÃO DE LANÇAMENTO"
- "ÚLTIMAS VAGAS DISPONÍVEIS"
- "OFERTA VÁLIDA APENAS HOJE"
- Ou qualquer outra mensagem

### Localização aproximada:
- Linha ~530 (barra vermelha no topo)

---

## 🎨 6. ADICIONAR AS IMAGENS

Coloque as imagens na pasta: `assets/images/`

**Nomes EXATOS (copie e cole):**
```
logo-whatsapp-10k.png
background-tech.jpg
hero-person.png
mockup-curso.png
foto-adonias.jpg
badge-preco.png
mockup-celular-preco.png (opcional)
```

⚠️ **ATENÇÃO:** 
- Nomes devem ser EXATAMENTE iguais
- `logo-whatsapp-10k.png` ≠ `Logo-Whatsapp-10k.PNG`
- Tudo em minúsculas
- Use hífen (-), não underscore (_)

---

## 🧪 7. TESTAR LOCALMENTE

Antes de subir:

1. ✅ Abra `index.html` no navegador
2. ✅ Todas as imagens aparecem?
3. ✅ Clique nos botões CTA
4. ✅ O link leva para o checkout da Kiwify?
5. ✅ Clique no botão WhatsApp
6. ✅ Abre o WhatsApp com sua mensagem?
7. ✅ Teste no celular (envie o arquivo por e-mail)

---

## 📱 8. CONFIGURAR PIXELS (Recomendado)

### Meta Pixel (Facebook Ads):

Se for fazer anúncios no Facebook, adicione o pixel:

1. Acesse: https://business.facebook.com/events_manager
2. Crie um pixel
3. Copie o código
4. Cole no `index.html` dentro da tag `<head>` (após linha ~12)

```html
<!-- Meta Pixel Code -->
<script>
!function(f,b,e,v,n,t,s){...código do pixel...}
fbq('init', 'SEU_PIXEL_ID');
fbq('track', 'PageView');
</script>
<!-- End Meta Pixel Code -->
```

### Google Analytics:

Para acompanhar visitantes:

1. Acesse: https://analytics.google.com
2. Crie uma propriedade
3. Copie o código GA4
4. Cole no `index.html` dentro da tag `<head>` (após linha ~12)

---

## ✅ CHECKLIST FINAL ANTES DE LANÇAR

- [ ] Substituí todos os 3 links de checkout
- [ ] Substituí o número do WhatsApp
- [ ] Substituí o CNPJ/CPF
- [ ] Coloquei todas as imagens na pasta correta
- [ ] Testei localmente no desktop
- [ ] Testei no celular
- [ ] Link do checkout funciona
- [ ] WhatsApp abre corretamente
- [ ] Imagens carregam
- [ ] Design está bonito
- [ ] Pixels instalados (se for usar ads)
- [ ] Fiz backup dos arquivos

---

## 🚀 DEPOIS DE LANÇAR

1. ✅ Teste o site online
2. ✅ Faça uma compra teste
3. ✅ Verifique se recebe notificação da Kiwify
4. ✅ Compartilhe o link com amigos para testar
5. ✅ Comece a divulgar!

---

## 🆘 PRECISA DE AJUDA?

**Não consegue encontrar algo?**

Use o atalho do seu editor:
- Windows: `Ctrl + F`
- Mac: `Cmd + F`

Digite o texto que quer buscar e substitua.

---

## 💡 DICA FINAL

**Não busque perfeição!**

- Lance com 80% pronto
- Melhore conforme recebe feedback
- Ajuste o que não estiver funcionando

**O importante é TER A PÁGINA NO AR! 🎯**

---

**Pronto para lançar? Vamos nessa! 🚀💰**
