* * *

title: <%= hoc_s(:title_how_to_promote) %> layout: wide nav: promote_nav

* * *

<% facebook = {:u=>"http://#{request.host}/us"}

twitter = {:url=>"http://hourofcode.com", :related=>'codeorg', :hashtags=>'', :text=>hoc_s(:twitter_default_text)} twitter[:hashtags] = 'HourOfCode' unless hoc_s(:twitter_default_text).include? '#OraEKodimit' %>

# Si të përfshihem

## 1. Përhap fjalën

Tregoju miqve të tu rreth **#HourOfCode**!

<%= view :share_buttons, facebook:facebook, twitter:twitter %>

## 2. Pyesni gjithë shkollën që të ofrojë një Orë Kodimi

[Dergo këtë email](%= resolve_url('/promote/resources#sample-emails') %) në drejtori dhe sfidoni të gjithat klasat ne shkollën tuaj për tu regjistruar. <% if @country == 'us' %> Një shkollë me fat në *çdo* shtet të SHBA (dhe Washington D.C.) do të fitoj $10,000 për teknologji. <% end %>

## 3. Pyesni punëdhënsin tuaj për tu përfshirë

[Dërgo këtë email](%= resolve_url('/promote/resources#sample-emails') %) te menaxheri juaj ose te drejtori ekzekutiv i kompanisë.

## 4. Promovo Orën e Kodimit brenda komunitetit tënd

[Rekruto një grup lokal](%= resolve_url('/promote/resources#sample-emails') %) — universiteti, klubi i futbollit, teatri. Nuk nevojitet shkolla për të mësuar aftësi të reja. Përdorni këto [postera, banera, stikers, video dhe më shumë](%= resolve_url('/promote/resources') %) për eventin tënd.

## 5. Pyet një zyrtar të zgjedhur për të përkrahur Orën e Kodimit

[Dërgo këtë email](%= resolve_url('/promote/resources#sample-emails') %) te përfaqësuesit lokal, këshilli i qytetit ose bordi i shkollës dhe ftoji që të vizitojnë shkollën tuaj për Orën e Kodimit. Ajo mund të ndihmojë të ndërtosh mbështetje për shkencën kompjuterike në zonën tuaj përtej një ore.