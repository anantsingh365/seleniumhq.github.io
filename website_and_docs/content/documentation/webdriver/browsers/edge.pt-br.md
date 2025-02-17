---
title: "Funcionalidade específica do Edge"
linkTitle: "Edge"
weight: 5
description: >-
    Estas capacidades e características são específicas ao navegador Microsoft Edge.
---

Microsoft Edge foi criado com recurso ao Chromium, cuja versão mais antiga suportada é a v79. 
Tal como o Chrome, a versão (maior) do edgedriver deve ser igual à do navegador Edge.

Todas as capacidades e opções encontradas na página [Chrome page]({{< ref "chrome.md" >}}) irão funcionar de igual forma para o Edge.

## Opções

Este é um exemplo de como iniciar uma sessão Edge com um conjunto de opções básicas:

{{< tabpane code=false langEqualsHeader=true >}}
{{< tab header="Java" >}}
{{< gh-codeblock path="/examples/java/src/test/java/dev/selenium/browsers/ChromeTest.java#L18-L19" >}}
{{< /tab >}}
{{% tab header="Python" %}}
{{< gh-codeblock path="/examples/python/tests/browsers/test_chrome.py#L6-L7" >}}
{{% /tab %}}
{{< tab header="CSharp" >}}
{{< gh-codeblock path="/examples/dotnet/SeleniumDocs/Browsers/ChromeTest.cs#L12-L13" >}}
{{< /tab >}}
{{< tab header="Ruby" >}}
{{< gh-codeblock path="/examples/ruby/spec/browsers/chrome_spec.rb#L7-L8" >}}
{{< /tab >}}
{{< tab header="JavaScript" >}}
{{< gh-codeblock path="/examples/javascript/test/getting_started/openEdgeTest.spec.js#L11-L16">}}
{{< /tab >}}
{{< tab header="Kotlin" >}}
{{< badge-code >}}
{{< /tab >}}
{{< /tabpane >}}

## Modo compatibilidade Internet Explorer

O Microsoft Edge pode ser controlado em modo "compatibilidade Internet Explorer", são usadas
classes do Internet Explorer Driver em conjunção com o Microsoft Edge.
Leia a [página Internet Explorer]({{< ref "internet_explorer.md" >}}) para mais detalhes.
