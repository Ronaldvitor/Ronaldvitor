
<!DOCTYPE HTML ><!--
 /*
 * (C) Copyright Blackboard Inc. 1998-2005 - All Rights Reserved
 *
 * Permission to use, copy, modify, and distribute this software
 * without prior explicit written approval is strictly prohibited.
 * Please refer to the file "copyright.html" for further important
 * copyright and licensing information.
 *
 * BLACKBOARD MAKES NO REPRESENTATIONS OR WARRANTIES ABOUT THE
 * SUITABILITY OF THE SOFTWARE, EITHER EXPRESS OR IMPLIED,
 * INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF
 * MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-
 * INFRINGEMENT. BLACKBOARD SHALL NOT BE LIABLE FOR ANY DAMAGES
 * SUFFERED BY LICENSEE AS A RESULT OF USING, MODIFYING OR
 * DISTRIBUTING THIS SOFTWARE OR ITS DERIVATIVES.
 */
 -->

<html  lang="pt-BR">
 <head>
  <title>Iniciar: AS I &ndash; Lingua Portuguesa - 80h_T12_CICLO_2_21_1</title>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  <meta id="request-method" name="request-method" content="GET">
  <meta name="author" content="Blackboard">
  <meta name="copyright" content="&copy; 1997-2021 Blackboard Inc. Todos os direitos reservados. Patente dos EUA Nº 7.493.396 e 7.558.853. Patentes adicionais pendentes.">
  <meta name="keywords" content="Blackboard">
  <meta http-equiv="Pragma" content="no-cache">
  <meta http-equiv="Expires" content="-1">
      <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    
<script type="text/javascript">(window.NREUM||(NREUM={})).loader_config={licenseKey:"232bf20b67",applicationID:"379357039"};window.NREUM||(NREUM={}),__nr_require=function(e,t,n){function r(n){if(!t[n]){var i=t[n]={exports:{}};e[n][0].call(i.exports,function(t){var i=e[n][1][t];return r(i||t)},i,i.exports)}return t[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var i=0;i<n.length;i++)r(n[i]);return r}({1:[function(e,t,n){function r(){}function i(e,t,n){return function(){return o(e,[u.now()].concat(c(arguments)),t?null:this,n),t?void 0:this}}var o=e("handle"),a=e(7),c=e(8),f=e("ee").get("tracer"),u=e("loader"),s=NREUM;"undefined"==typeof window.newrelic&&(newrelic=s);var d=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],p="api-",l=p+"ixn-";a(d,function(e,t){s[t]=i(p+t,!0,"api")}),s.addPageAction=i(p+"addPageAction",!0),s.setCurrentRouteName=i(p+"routeName",!0),t.exports=newrelic,s.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(e,t){var n={},r=this,i="function"==typeof t;return o(l+"tracer",[u.now(),e,n],r),function(){if(f.emit((i?"":"no-")+"fn-start",[u.now(),r,i],n),i)try{return t.apply(this,arguments)}catch(e){throw f.emit("fn-err",[arguments,this,e],n),e}finally{f.emit("fn-end",[u.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(e,t){m[t]=i(l+t)}),newrelic.noticeError=function(e,t){"string"==typeof e&&(e=new Error(e)),o("err",[e,u.now(),!1,t])}},{}],2:[function(e,t,n){function r(){return c.exists&&performance.now?Math.round(performance.now()):(o=Math.max((new Date).getTime(),o))-a}function i(){return o}var o=(new Date).getTime(),a=o,c=e(9);t.exports=r,t.exports.offset=a,t.exports.getLastTimestamp=i},{}],3:[function(e,t,n){function r(e){return!(!e||!e.protocol||"file:"===e.protocol)}t.exports=r},{}],4:[function(e,t,n){function r(e,t){var n=e.getEntries();n.forEach(function(e){"first-paint"===e.name?d("timing",["fp",Math.floor(e.startTime)]):"first-contentful-paint"===e.name&&d("timing",["fcp",Math.floor(e.startTime)])})}function i(e,t){var n=e.getEntries();n.length>0&&d("lcp",[n[n.length-1]])}function o(e){e.getEntries().forEach(function(e){e.hadRecentInput||d("cls",[e])})}function a(e){if(e instanceof m&&!g){var t=Math.round(e.timeStamp),n={type:e.type};t<=p.now()?n.fid=p.now()-t:t>p.offset&&t<=Date.now()?(t-=p.offset,n.fid=p.now()-t):t=p.now(),g=!0,d("timing",["fi",t,n])}}function c(e){d("pageHide",[p.now(),e])}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var f,u,s,d=e("handle"),p=e("loader"),l=e(6),m=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){f=new PerformanceObserver(r);try{f.observe({entryTypes:["paint"]})}catch(v){}u=new PerformanceObserver(i);try{u.observe({entryTypes:["largest-contentful-paint"]})}catch(v){}s=new PerformanceObserver(o);try{s.observe({type:"layout-shift",buffered:!0})}catch(v){}}if("addEventListener"in document){var g=!1,w=["click","keydown","mousedown","pointerdown","touchstart"];w.forEach(function(e){document.addEventListener(e,a,!1)})}l(c)}},{}],5:[function(e,t,n){function r(e,t){if(!i)return!1;if(e!==i)return!1;if(!t)return!0;if(!o)return!1;for(var n=o.split("."),r=t.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var i=null,o=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var c=navigator.userAgent,f=c.match(a);f&&c.indexOf("Chrome")===-1&&c.indexOf("Chromium")===-1&&(i="Safari",o=f[1])}t.exports={agent:i,version:o,match:r}},{}],6:[function(e,t,n){function r(e){function t(){e(a&&document[a]?document[a]:document[i]?"hidden":"visible")}"addEventListener"in document&&o&&document.addEventListener(o,t,!1)}t.exports=r;var i,o,a;"undefined"!=typeof document.hidden?(i="hidden",o="visibilitychange",a="visibilityState"):"undefined"!=typeof document.msHidden?(i="msHidden",o="msvisibilitychange"):"undefined"!=typeof document.webkitHidden&&(i="webkitHidden",o="webkitvisibilitychange",a="webkitVisibilityState")},{}],7:[function(e,t,n){function r(e,t){var n=[],r="",o=0;for(r in e)i.call(e,r)&&(n[o]=t(r,e[r]),o+=1);return n}var i=Object.prototype.hasOwnProperty;t.exports=r},{}],8:[function(e,t,n){function r(e,t,n){t||(t=0),"undefined"==typeof n&&(n=e?e.length:0);for(var r=-1,i=n-t||0,o=Array(i<0?0:i);++r<i;)o[r]=e[t+r];return o}t.exports=r},{}],9:[function(e,t,n){t.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(e,t,n){function r(){}function i(e){function t(e){return e&&e instanceof r?e:e?u(e,f,a):a()}function n(n,r,i,o,a){if(a!==!1&&(a=!0),!l.aborted||o){e&&a&&e(n,r,i);for(var c=t(i),f=v(n),u=f.length,s=0;s<u;s++)f[s].apply(c,r);var p=d[h[n]];return p&&p.push([b,n,r,c]),c}}function o(e,t){y[e]=v(e).concat(t)}function m(e,t){var n=y[e];if(n)for(var r=0;r<n.length;r++)n[r]===t&&n.splice(r,1)}function v(e){return y[e]||[]}function g(e){return p[e]=p[e]||i(n)}function w(e,t){s(e,function(e,n){t=t||"feature",h[n]=t,t in d||(d[t]=[])})}var y={},h={},b={on:o,addEventListener:o,removeEventListener:m,emit:n,get:g,listeners:v,context:t,buffer:w,abort:c,aborted:!1};return b}function o(e){return u(e,f,a)}function a(){return new r}function c(){(d.api||d.feature)&&(l.aborted=!0,d=l.backlog={})}var f="nr@context",u=e("gos"),s=e(7),d={},p={},l=t.exports=i();t.exports.getOrSetContext=o,l.backlog=d},{}],gos:[function(e,t,n){function r(e,t,n){if(i.call(e,t))return e[t];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:r,writable:!0,enumerable:!1}),r}catch(o){}return e[t]=r,r}var i=Object.prototype.hasOwnProperty;t.exports=r},{}],handle:[function(e,t,n){function r(e,t,n,r){i.buffer([e],r),i.emit(e,t,n)}var i=e("ee").get("handle");t.exports=r,r.ee=i},{}],id:[function(e,t,n){function r(e){var t=typeof e;return!e||"object"!==t&&"function"!==t?-1:e===window?0:a(e,o,function(){return i++})}var i=1,o="nr@id",a=e("gos");t.exports=r},{}],loader:[function(e,t,n){function r(){if(!E++){var e=x.info=NREUM.info,t=l.getElementsByTagName("script")[0];if(setTimeout(u.abort,3e4),!(e&&e.licenseKey&&e.applicationID&&t))return u.abort();f(h,function(t,n){e[t]||(e[t]=n)});var n=a();c("mark",["onload",n+x.offset],null,"api"),c("timing",["load",n]);var r=l.createElement("script");r.src="https://"+e.agent,t.parentNode.insertBefore(r,t)}}function i(){"complete"===l.readyState&&o()}function o(){c("mark",["domContent",a()+x.offset],null,"api")}var a=e(2),c=e("handle"),f=e(7),u=e("ee"),s=e(5),d=e(3),p=window,l=p.document,m="addEventListener",v="attachEvent",g=p.XMLHttpRequest,w=g&&g.prototype;if(d(p.location)){NREUM.o={ST:setTimeout,SI:p.setImmediate,CT:clearTimeout,XHR:g,REQ:p.Request,EV:p.Event,PR:p.Promise,MO:p.MutationObserver};var y=""+location,h={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-1208.min.js"},b=g&&w&&w[m]&&!/CriOS/.test(navigator.userAgent),x=t.exports={offset:a.getLastTimestamp(),now:a,origin:y,features:{},xhrWrappable:b,userAgent:s};e(1),e(4),l[m]?(l[m]("DOMContentLoaded",o,!1),p[m]("load",r,!1)):(l[v]("onreadystatechange",i),p[v]("onload",r)),c("mark",["firstbyte",a.getLastTimestamp()],null,"api");var E=0}},{}],"wrap-function":[function(e,t,n){function r(e,t){function n(t,n,r,f,u){function nrWrapper(){var o,a,s,p;try{a=this,o=d(arguments),s="function"==typeof r?r(o,a):r||{}}catch(l){i([l,"",[o,a,f],s],e)}c(n+"start",[o,a,f],s,u);try{return p=t.apply(a,o)}catch(m){throw c(n+"err",[o,a,m],s,u),m}finally{c(n+"end",[o,a,p],s,u)}}return a(t)?t:(n||(n=""),nrWrapper[p]=t,o(t,nrWrapper,e),nrWrapper)}function r(e,t,r,i,o){r||(r="");var c,f,u,s="-"===r.charAt(0);for(u=0;u<t.length;u++)f=t[u],c=e[f],a(c)||(e[f]=n(c,s?f+r:r,i,f,o))}function c(n,r,o,a){if(!m||t){var c=m;m=!0;try{e.emit(n,r,o,t,a)}catch(f){i([f,n,r,o],e)}m=c}}return e||(e=s),n.inPlace=r,n.flag=p,n}function i(e,t){t||(t=s);try{t.emit("internal-error",e)}catch(n){}}function o(e,t,n){if(Object.defineProperty&&Object.keys)try{var r=Object.keys(e);return r.forEach(function(n){Object.defineProperty(t,n,{get:function(){return e[n]},set:function(t){return e[n]=t,t}})}),t}catch(o){i([o],n)}for(var a in e)l.call(e,a)&&(t[a]=e[a]);return t}function a(e){return!(e&&e instanceof Function&&e.apply&&!e[p])}function c(e,t){var n=t(e);return n[p]=e,o(e,n,s),n}function f(e,t,n){var r=e[t];e[t]=c(r,n)}function u(){for(var e=arguments.length,t=new Array(e),n=0;n<e;++n)t[n]=arguments[n];return t}var s=e("ee"),d=e(8),p="nr@original",l=Object.prototype.hasOwnProperty,m=!1;t.exports=r,t.exports.wrapFunction=c,t.exports.wrapInPlace=f,t.exports.argsToArray=u},{}]},{},["loader"]);</script>
  <link rel="SHORTCUT ICON" type="image/x-icon" href="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/ui/bb-icon3.ico">
     <link rel="stylesheet" type="text/css" href="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/common/shared.css?v=3900.10.0-rel.29+3b9a0fc" id="css_0">
     <link rel="stylesheet" type="text/css" href="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/themes/as_2015/theme.css?v=3900.10.0-rel.29+3b9a0fc" id="css_1">
     <link rel="stylesheet" type="text/css" href="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/themes/as_2015/app_nav.css?v=3900.10.0-rel.29+3b9a0fc" id="css_2">
     <link rel="stylesheet" type="text/css" href="/branding/_1_1/brand.css?ts=1596822834633&v=3900.10.0-rel.29+3b9a0fc" id="css_3">
     <link rel="stylesheet" type="text/css" href="/webapps/assessment/css/assessment.css?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc" id="css_4">
     <link rel="stylesheet" type="text/css" href="/webapps/assessment/css/as_2015/assessment.css?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc" id="css_5">
     <link rel="stylesheet" type="text/css" href="/webapps/vtbe-tinymce/css/prism/prism.css?v=3900.10.0-rel.29+3b9a0fc" id="css_6">
     <link rel="stylesheet" type="text/css" href="/webapps/videointegration/css/video-integration.css?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc" id="css_7">
          
       <link rel="stylesheet" type="text/css" media="print" href="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/ui/styles/print.css?v=3900.10.0-rel.29+3b9a0fc">
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/i18n.js?v=3900.10.0-rel.29+3b9a0fc"></script>
      <script language='javascript' type='text/javascript'>

var JS_RESOURCES = new Object();

function _init_bundle_JS_RESOURCES() {

    JS_RESOURCES['validation.email'] = 'Um endereço de e-mail totalmente qualificado (por exemplo, info@blackboard.com) deve ser inserido.';
    JS_RESOURCES['validation.radio.required'] = 'Selecione para continuar.';
    JS_RESOURCES['assessment.incomplete.confirm.backtrackProhibited.survey'] = 'As perguntas a seguir podem estar incompletas:\n {0}\nClique em cancelar para retornar à pesquisa. Clique em OK para salvar a resposta incompleta.';
    JS_RESOURCES['common.list.separator.comma'] = '{0}, {1}';
    JS_RESOURCES['active.filter.search.terms'] = 'Termos da pesquisa';
    JS_RESOURCES['validation.points.decimal.places.error.location'] = 'Os valores de pontos são limitados a 5 casas decimais: {0}.';
    JS_RESOURCES['validation.maximum_length.plural'] = '{0} não pode conter mais de {1} caracteres.\nReduza o tamanho da entrada em {2} caracteres.';
    JS_RESOURCES['assessment.incomplete.confirm.backtrackProhibited'] = 'As perguntas a seguir podem estar incompletas:\n {0}\nClique em cancelar para retornar ao teste. Clique em OK para salvar a resposta incompleta.';
    JS_RESOURCES['validation.multiSelect.minItems'] = 'A caixa de multi-seleção deve conter no mínimo {0} número de itens.';
    JS_RESOURCES['validation.cmp_field.required'] = 'Deve-se informar um valor para {0}\nquando o campo {1} não estiver vazio';
    JS_RESOURCES['warning.email'] = 'É obrigatório o fornecimento de um E-mail. Não será possível aos usuários utilizar parte do sistema se não fornecerem um E-mail.';
    JS_RESOURCES['validation.maximum_length.no_name.singular'] = 'Não deve conter mais que {0} caracteres.\nReduza o tamanho da entrada em 1 caractere.';
    JS_RESOURCES['validation.multiSelect.maxItems'] = 'A caixa de multi-seleção não deve conter mais de {0} número de itens.';
    JS_RESOURCES['validation.number'] = 'Deve-se informar um valor numérico válido para {0}.';
    JS_RESOURCES['validation.date.required'] = 'Um valor de data completo deve ser fornecido: {0}.';
    JS_RESOURCES['portalmodule.section.remove'] = 'Excluir: {0}?';
    JS_RESOURCES['show.helptext'] = 'Mostrar texto de ajuda';
    JS_RESOURCES['validation.password'] = 'A senha não pode estar em branco nem conter apenas espaços.';
    JS_RESOURCES['validation.percent'] = 'Deve-se informar um valor de percentagem válido entre 0 e 100.';
    JS_RESOURCES['validation.mismatch'] = 'Os valores informados para {0} não correspondem.\nConfirme {0}.';
    JS_RESOURCES['validation.maximum_length.no_name.plural'] = 'Não deve conter mais que {0} caracteres.\nReduza o tamanho da entrada em {1} caracteres.';
    JS_RESOURCES['validation.invalid_value'] = 'Valor numérico inválido fornecido: {0}.';
    JS_RESOURCES['field_name.substitute'] = 'campo de introdução {0}';
    JS_RESOURCES['validation.required'] = 'Deve-se informar um valor para {0}.';
    JS_RESOURCES['active.filter.free.form.text.blank'] = 'Especificar um valor no campo de texto da pesquisa';
    JS_RESOURCES['validate.alignment.missing.content'] = 'Você selecionou alinhamentos, mas não selecionou qualquer conteúdo alinhável para copiar.';
    JS_RESOURCES['validation.system_role.reserve'] = '"bb" não é permitido no início de um código de função.';
    JS_RESOURCES['validation.date_past'] = 'A data de término não pode ser anterior a data de início.';
    JS_RESOURCES['validation.invalid_chars'] = 'Contém caracteres ilegais: {0}.\nExcluir estes caracteres: {1}';
    JS_RESOURCES['confirm.delete_item_value'] = 'Este item {0} será excluído. Continuar?';
    JS_RESOURCES['hide.helptext'] = 'Ocultar Texto de Ajuda';
    JS_RESOURCES['validate.range.lessthen.str'] = 'Menos de {0}';
    JS_RESOURCES['validation.date_past.confirm'] = 'A hora está no passado.\nManter esta hora?';
    JS_RESOURCES['validate.login.invalid.username.or.pass'] = 'Inserir um nome do usuário e senha.';
    JS_RESOURCES['validation.negative'] = 'Um valor válido não negativo deve ser informado: {0}.';
    JS_RESOURCES['validation.url'] = 'Um URL válido (por exemplo, http://www.myschool.edu) deve ser inserido.';
    JS_RESOURCES['validate.range.overlap'] = 'critérios ({0}) sobrepõem-se aos critérios ({1}).';
    JS_RESOURCES['validate.range.between.str'] = 'Entre {0} e {1}';
    JS_RESOURCES['validation.portal.tool.items.remove'] = 'Excluir: {0}?';
    JS_RESOURCES['validation.association.refresh.confirm'] = 'As informações de itens associados poderiam ter sido atualizadas.\nClique em "OK" para atualizar a lista ou clique em "Cancelar" para manter a página atual.';
    JS_RESOURCES['validate.enrolloptions.error.codeconflict'] = 'A opção do Código do acesso da inscrição está em conflito com a seleção da inscrição liderada por {instructor}.';
    JS_RESOURCES['validation.points.decimal.places'] = 'Os valores de pontos são limitados a 5 casas decimais.';
    JS_RESOURCES['validation.option.required'] = 'Pelo menos uma opção da lista deve ser selecionada.';
    JS_RESOURCES['list.checkToSelectAllItems'] = 'Marcar para selecionar todos os itens';
    JS_RESOURCES['active.filter.changed.alert'] = 'os critérios agora contêm';
    JS_RESOURCES['vtbe.artifact.footer.validate.nameIfSaveArtifact'] = 'Especifique um nome para Salvar como objeto reutilizável.';
    JS_RESOURCES['validate.invalidate.number'] = 'Insira um número válido em vez de {0}.';
    JS_RESOURCES['validation.valid_course_id'] = 'Código do Curso contém caracteres inválidos ou caracteres de vários bytes.';
    JS_RESOURCES['assessment.incomplete.confirm'] = 'As perguntas a seguir podem estar incompletas:\n {0}\nClique em cancelar para retornar ao teste. Clique em OK para enviar a avaliação.';
    JS_RESOURCES['validate.enrolloptions.error.nooption'] = 'Aviso: Escolha a opção Liderada por {instructor} ou a  Auto-inscrição.';
    JS_RESOURCES['validation.date_equal'] = 'A data de início não pode ser igual a data de término.';
    JS_RESOURCES['validation.cmp_field.rejected'] = '{0} não pode ser utilizado sem um valor {1} correspondente.';
    JS_RESOURCES['validation.time.required'] = 'Um valor de data completo deve ser fornecido: {0}.';
    JS_RESOURCES['validation.integer_number'] = 'É necessário inserir um valor numérico inteiro: {0}.';
    JS_RESOURCES['validation.maximum_length'] = 'Não deve conter mais de 255 caracteres';
    JS_RESOURCES['validate.enrolloptions.error.emailrequestconflict'] = 'A opção de inscrição por e-mail selecionada está em conflito com a seleção da auto-inscrição.';
    JS_RESOURCES['invalid_char.space'] = 'espaço';
    JS_RESOURCES['validate.range.morethen.str'] = 'Mais de {0}';
    JS_RESOURCES['notification.submit'] = 'Esta ação já foi enviada.\nAguarde até a ação estar concluída.';
    JS_RESOURCES['validation.plain_text.confirm'] = 'Para mostrar equações corretamente neste documento, tem de selecionar o formato Texto Inteligente ou HTML .\nClique em OK para salvar no formato Texto Simples selecionado ou clique em Cancelar para selecionar um novo formato.';
    JS_RESOURCES['invalid_char.comma'] = 'vírgula';
    JS_RESOURCES['validation.allow_negtive.percent'] = 'Deve ser inserido um valor percentual válido entre - 100 e 100.';
    JS_RESOURCES['confirm.remove_item'] = 'Essa ação é final e não pode ser desfeita. Continuar?';
    JS_RESOURCES['list.uncheckToDeselectAllItems'] = 'Desmarcar para remover a seleção de todos os itens';
    JS_RESOURCES['validation.maximum_length.singular'] = '{0} não pode conter mais de {1} caracteres.\nRetire um carácter ao tamanho da entrada.';
    JS_RESOURCES['validation.rubric.decimalplaces'] = 'Excesso de casas decimais. O máximo é 5.';
    JS_RESOURCES['validation.minimum_length'] = 'Deve-se informar um mínimo de {0} caracteres para {1}.';
    JS_RESOURCES['vtbe.artifact.footer.validate.saveLocationIfSaveArtifact'] = 'Especificar um local para o Objeto reutilizável.';
    JS_RESOURCES['assessment.incomplete.confirm.survey'] = 'As perguntas a seguir podem estar incompletas:\n {0}\nClique em cancelar para retornar à pesquisa. Clique em OK para enviar a avaliação.';
    JS_RESOURCES['validation.image_type'] = '{0} não é um tipo de imagem conhecida e pode não aparecer corretamente.';
    JS_RESOURCES['validate.invalidate.number.space'] = 'Espaço';

    JS_RESOURCES.getString = i18n_get_string;
    JS_RESOURCES.getFormattedString = i18n_get_formatted_string;

}

_init_bundle_JS_RESOURCES();

</script>
<script language='javascript' type='text/javascript'>

var LOCALE_SETTINGS = new Object();

function _init_bundle_LOCALE_SETTINGS() {

    LOCALE_SETTINGS['LOCALE_SETTINGS.ADDRESS_FIELD_ORDER'] = 'STREET_1 STREET_2 CITY STATE ZIP_CODE COUNTRY';
    LOCALE_SETTINGS['number_format.exponent'] = 'eE';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.COLUMN.2'] = '{1}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.YEAR_CHARACTER.03255'] = '';
    LOCALE_SETTINGS['BBI18N.SOLARIS_CHARSET'] = 'ISO8859-1';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.COLUMN.1'] = '{0}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_COLUMN_FORMAT_MONTH.03255'] = 'ddd';
    LOCALE_SETTINGS['LOCALE_SETTINGS.internal_date_format'] = 'dd/MM/yy';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TITLE_FORMAT_MONTH.03259'] = 'MMMM \'de\' yyyy';
    LOCALE_SETTINGS['LOCALE_SETTINGS.TIME_ORDER.00519'] = 'HMP';
    LOCALE_SETTINGS['float.format'] = '^([0-9]{1,3}(\\.[0-9]{3})*(\\,[0-9]+)?|\\,[0-9]+)?$';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.SORT_COLUMN'] = 'familyName';
    LOCALE_SETTINGS['LOCALE_SETTINGS.SHORT'] = '{1} {3}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_SHORT.02097'] = 'DOM SEG TER QUA QUI SEX SÁB';
    LOCALE_SETTINGS['float.allow.negative.format'] = '^((([-]?[0-9]{1,3}(\\.[0-9]{3})*)|[-]?[0-9]*)(\\,[0-9]+)?|\\,[0-9]+)?$';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TYPE'] = 'GREGORIAN';
    LOCALE_SETTINGS['LOCALE_SETTINGS.GIVEN_INITIAL_FAMILY_NAME'] = '{4} {3}';
    LOCALE_SETTINGS['efloat.format'] = '^[+-]?[0-9]*(\\,[0-9]+)?([eE][+-]?[0-9]+)?$';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TITLE_FORMAT_WEEK.03260'] = 'd[ MMM][ yyyy]{\'&#8212;\'d MMM yyyy}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_FULL.02100'] = 'Janeiro Fevereiro Março Abril Maio Junho Julho Agosto Setembro Outubro Novembro Dezembro';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NUMBERS_HIJRI_LOCALIZED.00521'] = 'NO';
    LOCALE_SETTINGS['LOCALE_SETTINGS.LONG'] = '{0} {1} {2} {3}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.WORK_FIELD_ORDER'] = 'JOB_TITLE DEPARTMENT COMPANY B_PHONE_1 B_PHONE_2 B_FAX';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_FULL_HIJRI.02100'] = 'Muḥarram,Ṣafar,Rabīʿ\'al-Awwal,Rabīʿ\'ath-Thānī,Jumādā\'al-Ūlā,Jumādā\'ath-Thāniya,Rajab,Shaʿbān,Ramaḍān,Shawwāl,Dhū\'al-Qaʿda,Dhū\'al-Ḥijja';
    LOCALE_SETTINGS['LOCALE_SETTINGS.GREETING'] = 'Bem-vindo, {1}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_SHORT.00520'] = 'Jan Fev Mar Abr Maio Jun Jul Ago Set Out Nov Dez';
    LOCALE_SETTINGS['number_format.thousands_sep'] = '.';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_COLUMN_FORMAT_WEEK.03256'] = 'ddd, dd/MM';
    LOCALE_SETTINGS['LOCALE_SETTINGS.SHORT_SURNAME'] = '{3}, {1}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.AM_PM.00522'] = 'AM PM';
    LOCALE_SETTINGS['number_format.negative_prefix'] = '-';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DATE_ORDER.00519'] = 'DMY';
    LOCALE_SETTINGS['LOCALE_SETTINGS.PHONE_FIELD_ORDER'] = 'H_PHONE_1 H_PHONE_2 H_FAX M_PHONE';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_MIN.02099'] = 'DOM SEG TER QUA QUI SEX SÁB';
    LOCALE_SETTINGS['LOCALE_SETTINGS.24HR_SUPPORT.03208'] = '1';
    LOCALE_SETTINGS['LOCALE_SETTINGS.FIRST_DAY_OF_WEEK.03207'] = '0';
    LOCALE_SETTINGS['BBI18N.WINDOWS_CHARSET'] = 'ISO-8859-1';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_SHORT_HIJRI.00520'] = 'Muḥarram,Ṣafar,Rabīʿ\'I,Rabīʿ\'II,Jumādā\'I,Jumādā\'II,Rajab,Shaʿbān,Ramaḍān,Shawwāl,Dhū\'al-Qaʿda,Dhū\'al-Ḥijja';
    LOCALE_SETTINGS['BBI18N.LINUX_CHARSET'] = 'iso88591';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_CHARACTER.03253'] = '';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_CHARACTER.03254'] = '';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.COLUMN_ORDER'] = 'title,givenName,middleName,familyName,suffix,otherName';
    LOCALE_SETTINGS['number_format.decimal_point'] = ',';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TITLE_FORMAT_DAY.03258'] = 'dddd, d MMM yyyy';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAYS.00521'] = '01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31';
    LOCALE_SETTINGS['LOCALE_SETTINGS.OVERRIDE_LONG_TIME_WITH_FULL'] = 'false';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_FULL.02098'] = 'Domingo Segunda-feira Terça-feira Quarta-feira Quinta-feira Sexta-feira Sábado';
    LOCALE_SETTINGS['LOCALE_SETTINGS.date_display_pattern'] = 'DD/MM/YY';
    LOCALE_SETTINGS['LOCALE_SETTINGS.EXTENDED_SURNAME'] = '{3}';
    LOCALE_SETTINGS['thousand.sep.format'] = '\\.';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NUMBERS_HIJRI.00521'] = '0 1 2 3 4 5 6 7 8 9';
    LOCALE_SETTINGS['LOCALE_SETTINGS.ADDRESS_ORDER.07832'] = 'street,city,region,postal_code,country';
    LOCALE_SETTINGS['number_format.negative_suffix'] = '';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_COLUMN_FORMAT_DAY.03257'] = 'dddd, dd/MM';

    LOCALE_SETTINGS.getString = i18n_get_string;
    LOCALE_SETTINGS.getFormattedString = i18n_get_formatted_string;

}

_init_bundle_LOCALE_SETTINGS();

</script>

      <script language='javascript' type='text/javascript'>

var LOCALE_SETTINGS = new Object();

function _init_bundle_LOCALE_SETTINGS() {

    LOCALE_SETTINGS['LOCALE_SETTINGS.ADDRESS_FIELD_ORDER'] = 'STREET_1 STREET_2 CITY STATE ZIP_CODE COUNTRY';
    LOCALE_SETTINGS['number_format.exponent'] = 'eE';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.COLUMN.2'] = '{1}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.YEAR_CHARACTER.03255'] = '';
    LOCALE_SETTINGS['BBI18N.SOLARIS_CHARSET'] = 'ISO8859-1';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.COLUMN.1'] = '{0}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_COLUMN_FORMAT_MONTH.03255'] = 'ddd';
    LOCALE_SETTINGS['LOCALE_SETTINGS.internal_date_format'] = 'dd/MM/yy';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TITLE_FORMAT_MONTH.03259'] = 'MMMM \'de\' yyyy';
    LOCALE_SETTINGS['LOCALE_SETTINGS.TIME_ORDER.00519'] = 'HMP';
    LOCALE_SETTINGS['float.format'] = '^([0-9]{1,3}(\\.[0-9]{3})*(\\,[0-9]+)?|\\,[0-9]+)?$';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.SORT_COLUMN'] = 'familyName';
    LOCALE_SETTINGS['LOCALE_SETTINGS.SHORT'] = '{1} {3}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_SHORT.02097'] = 'DOM SEG TER QUA QUI SEX SÁB';
    LOCALE_SETTINGS['float.allow.negative.format'] = '^((([-]?[0-9]{1,3}(\\.[0-9]{3})*)|[-]?[0-9]*)(\\,[0-9]+)?|\\,[0-9]+)?$';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TYPE'] = 'GREGORIAN';
    LOCALE_SETTINGS['LOCALE_SETTINGS.GIVEN_INITIAL_FAMILY_NAME'] = '{4} {3}';
    LOCALE_SETTINGS['efloat.format'] = '^[+-]?[0-9]*(\\,[0-9]+)?([eE][+-]?[0-9]+)?$';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TITLE_FORMAT_WEEK.03260'] = 'd[ MMM][ yyyy]{\'&#8212;\'d MMM yyyy}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_FULL.02100'] = 'Janeiro Fevereiro Março Abril Maio Junho Julho Agosto Setembro Outubro Novembro Dezembro';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NUMBERS_HIJRI_LOCALIZED.00521'] = 'NO';
    LOCALE_SETTINGS['LOCALE_SETTINGS.LONG'] = '{0} {1} {2} {3}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.WORK_FIELD_ORDER'] = 'JOB_TITLE DEPARTMENT COMPANY B_PHONE_1 B_PHONE_2 B_FAX';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_FULL_HIJRI.02100'] = 'Muḥarram,Ṣafar,Rabīʿ\'al-Awwal,Rabīʿ\'ath-Thānī,Jumādā\'al-Ūlā,Jumādā\'ath-Thāniya,Rajab,Shaʿbān,Ramaḍān,Shawwāl,Dhū\'al-Qaʿda,Dhū\'al-Ḥijja';
    LOCALE_SETTINGS['LOCALE_SETTINGS.GREETING'] = 'Bem-vindo, {1}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_SHORT.00520'] = 'Jan Fev Mar Abr Maio Jun Jul Ago Set Out Nov Dez';
    LOCALE_SETTINGS['number_format.thousands_sep'] = '.';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_COLUMN_FORMAT_WEEK.03256'] = 'ddd, dd/MM';
    LOCALE_SETTINGS['LOCALE_SETTINGS.SHORT_SURNAME'] = '{3}, {1}';
    LOCALE_SETTINGS['LOCALE_SETTINGS.AM_PM.00522'] = 'AM PM';
    LOCALE_SETTINGS['number_format.negative_prefix'] = '-';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DATE_ORDER.00519'] = 'DMY';
    LOCALE_SETTINGS['LOCALE_SETTINGS.PHONE_FIELD_ORDER'] = 'H_PHONE_1 H_PHONE_2 H_FAX M_PHONE';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_MIN.02099'] = 'DOM SEG TER QUA QUI SEX SÁB';
    LOCALE_SETTINGS['LOCALE_SETTINGS.24HR_SUPPORT.03208'] = '1';
    LOCALE_SETTINGS['LOCALE_SETTINGS.FIRST_DAY_OF_WEEK.03207'] = '0';
    LOCALE_SETTINGS['BBI18N.WINDOWS_CHARSET'] = 'ISO-8859-1';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_SHORT_HIJRI.00520'] = 'Muḥarram,Ṣafar,Rabīʿ\'I,Rabīʿ\'II,Jumādā\'I,Jumādā\'II,Rajab,Shaʿbān,Ramaḍān,Shawwāl,Dhū\'al-Qaʿda,Dhū\'al-Ḥijja';
    LOCALE_SETTINGS['BBI18N.LINUX_CHARSET'] = 'iso88591';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_CHARACTER.03253'] = '';
    LOCALE_SETTINGS['LOCALE_SETTINGS.MONTH_CHARACTER.03254'] = '';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NAME.COLUMN_ORDER'] = 'title,givenName,middleName,familyName,suffix,otherName';
    LOCALE_SETTINGS['number_format.decimal_point'] = ',';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_TITLE_FORMAT_DAY.03258'] = 'dddd, d MMM yyyy';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAYS.00521'] = '01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31';
    LOCALE_SETTINGS['LOCALE_SETTINGS.OVERRIDE_LONG_TIME_WITH_FULL'] = 'false';
    LOCALE_SETTINGS['LOCALE_SETTINGS.DAY_FULL.02098'] = 'Domingo Segunda-feira Terça-feira Quarta-feira Quinta-feira Sexta-feira Sábado';
    LOCALE_SETTINGS['LOCALE_SETTINGS.date_display_pattern'] = 'DD/MM/YY';
    LOCALE_SETTINGS['LOCALE_SETTINGS.EXTENDED_SURNAME'] = '{3}';
    LOCALE_SETTINGS['thousand.sep.format'] = '\\.';
    LOCALE_SETTINGS['LOCALE_SETTINGS.NUMBERS_HIJRI.00521'] = '0 1 2 3 4 5 6 7 8 9';
    LOCALE_SETTINGS['LOCALE_SETTINGS.ADDRESS_ORDER.07832'] = 'street,city,region,postal_code,country';
    LOCALE_SETTINGS['number_format.negative_suffix'] = '';
    LOCALE_SETTINGS['LOCALE_SETTINGS.CALENDAR_COLUMN_FORMAT_DAY.03257'] = 'dddd, dd/MM';

    LOCALE_SETTINGS.getString = i18n_get_string;
    LOCALE_SETTINGS.getFormattedString = i18n_get_formatted_string;

}

_init_bundle_LOCALE_SETTINGS();

</script>

         <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/cdn.js"></script>
    <script type="text/javascript" src="/groupjs/CD2F9A0A722BE53B49657A16FC10A7B4.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr_open/interface/UserDataDWRFacade.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr_open/interface/MashupDWRFacade.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/titlebartagutils.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr_open/engine.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr/interface/AssessmentDWRFacade.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/groupjs/8184C106237416EC96C8F4A6571B889D.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/ngui/widget.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr_open/interface/CourseMenuDWRFacade.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr_open/interface/UserPageInstructionsSettingDWRFacade.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/dwr/engine.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/ngui/breadcrumbs.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/ngui/tree.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/ngui/coursemenu.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/javascript/dwr/util.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/groupjs/E390CA0D26F30574E9C8617C5BFE9530.js?v=3900.10.0-rel.29+3b9a0fc"></script>
    <script type="text/javascript" src="/webapps/assessment/dwr_open/interface/UserDWRFacade.js?v=3900.10.0-rel.29+3b9a0fc_3900.10.0-rel.29+3b9a0fc"></script>
    </head>
  <body id="learn-oe-body" >
  
<div class=quickLinksOnly><h1 class="hideoff hideFromQuickLinks">Abrir links rápidos</h1><div id=quick_links_wrap><a id=quick_links_lightbox_link href="#" onclick="quickLinks.lightboxHelper.toggleLightbox(); return false;" role=button aria-haspopup=true tabindex=1 title="Abrir&#x20;links&#x20;r&aacute;pidos">Links rápidos</a></div><div id=quickLinksLightboxDiv class=hideoff aria-hidden=true style="display:none"><div class=ax-content><div class=content-lite><div id=quick_links_landmarks_section><h2 class=hideFromQuickLinks>Referências de página</h2><ul class=shortcut-list id=quick_links_landmark_list></ul></div><div id=quick_links_headings_section><h2 class=hideFromQuickLinks>Definir conteúdo</h2><ul class=shortcut-list id=quick_links_heading_list></ul></div></div><div id=quick_links_hotkeys_section class=legend><h2 class=hideFromQuickLinks>Atalhos do teclado</h2><ul class=keycombos id=quick_links_hotkey_list></ul></div></div></div></div>
<div id="globalNavPageContentArea">

<h2 class="hideoff">
 Local atual
</h2>

<div id="breadcrumbs" class="breadcrumbs clearfix ">
 <div class="breadcrumb-controls clearfix" id="breadcrumb_controls_id">





<div id="helpTextToggle" class="helpLink hidden">
  <a href="#" id="helpTextToggleLink" class="browseIcon">
	<img id="helpTextToggleImg" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/images-ltr/ci/ng/small_help_on2.gif" alt="Desativar e ativar o texto de ajuda"/></a>
</div>
 <input type='hidden' name='showHelperSetting' id='showHelperSetting' value=''>
 </div>

 <div class="path  noToggle" role="navigation">
 <ol class="clearfix">
    	<li
    class="root"
		    > <a href="/webapps/blackboard/execute/courseMain?course_id=_730273_1"  title="Lingua Portuguesa - 80h_T12_CICLO_2_21_1">        <span id="crumb_1">
                      Lingua Portuguesa - 80h_T12_CICLO_2_21_1
                  </span>
      </a>          </li>
   	<li
        > <a href="/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9341986_1&mode=reset"  title="Material Referencial">        <span id="crumb_2">
                      Material Referencial
                  </span>
      </a>          </li>
   	<li
        > <a href="/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9341999_1&mode=reset"  title="ATIVIDADES DA DISCIPLINA">        <span id="crumb_3">
                      ATIVIDADES DA DISCIPLINA
                  </span>
      </a>          </li>
   	<li
    class="placeholder"        >         <span id="crumb_4">
                      Iniciar: AS I
                  </span>
                </li>
  </ol>
 </div>

</div>

<div class="locationPane">
 <nav role="navigation" aria-label="Course Menu" id="navigationPane" class="navigationPane ">
 
 <div id="menuWrap" class="menuWrap" >
  <div id="puller" >
  <a id="menuPuller" class="clickpuller" title="Ocultar Menu Curso" href="#">
   <img id="expander" alt="Ocultar Menu Curso" src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/images/spacer.gif"/>
  </a>
 </div>
<div class="menuWrap-inner">
  <div id="courseMenuPalette" class="navPalette listCm navPaletteExpCol"><div class="actionBarMicro clearfix"><h2 class="hideoff">Opções de gerenciamento do menu</h2><ul id="courseMenuPalette_actionbar" class="nav clearfix u_floatThis-left"></ul><ul class="nav clearfix u_floatThis-right"><li id="refreshMenuLink" class="secondaryButton "><a href="#" title="Atualizar"><span><img src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/images/ci/ng/small_refresh.gif" alt="Atualizar"></span></a></li><li id="courseMapButton" class="secondaryButton "><a href="#" title="Exibir menu do curso em uma janela"><span><img src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/images/ci/ng/small_new_window.gif" alt="Exibir menu do curso em uma janela"></span></a></li></ul></div><div class="navPaletteContent"><h2 class="hideoff" tabindex="-1">Menu curso:</h2><div id="courseMenuPalette_paletteTitleHeading"><div class="navPaletteTitle"><h3><a href="#" role="button" aria-expanded="true" class="comboLink" aria-controls="courseMenuPalette_contents" title="Recolher Lingua Portuguesa - 80h_T12_CICLO_2_21_1" id="courseMenu_link">Lingua Portuguesa - 80h_T12_CICLO_2_21_1</a></h3><h3><a href="/webapps/blackboard/execute/courseMain?course_id=_730273_1" target="" class="submenuLink" id="courseMenu_combo" title="Ir para a página Entrada do curso"><img src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/images/ci/icons/generic_dbl_arrow_right.gif" alt="Página inicial do curso"></a></h3></div></div><ul id="courseMenuPalette_contents" class="courseMenu"><li id="paletteItem:_4751857_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&tool_id=_111_1&tool_type=TOOL&mode=view&mode=reset" target="_self"><span title="Avisos">Avisos</span></a></li><li id="paletteItem:_4751855_1" class="clearfix "><a href="/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9318659_1&mode=reset" target="_self"><span title="Calendário">Calendário</span></a></li><li id="paletteItem:_4756354_1" class="clearfix "><a href="/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9341986_1&mode=reset" target="_self"><span title="Material Referencial">Material Referencial</span></a></li><li id="paletteItem:_4756357_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756357_1&mode=view&mode=reset" target="_self"><span title="Unidade I">Unidade I</span></a></li><li id="paletteItem:_4756358_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756358_1&mode=view&mode=reset" target="_self"><span title="Unidade II">Unidade II</span></a></li><li id="paletteItem:_4756359_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756359_1&mode=view&mode=reset" target="_self"><span title="Unidade III">Unidade III</span></a></li><li id="paletteItem:_4756360_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756360_1&mode=view&mode=reset" target="_self"><span title="Unidade IV">Unidade IV</span></a></li><li id="paletteItem:_4756361_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756361_1&mode=view&mode=reset" target="_self"><span title="Unidade V">Unidade V</span></a></li><li id="paletteItem:_4756362_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756362_1&mode=view&mode=reset" target="_self"><span title="Unidade VI">Unidade VI</span></a></li><li id="paletteItem:_4756363_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&toc_id=_4756363_1&mode=view&mode=reset" target="_self"><span title="Atividades da Disciplina">Atividades da Disciplina</span></a></li><li id="paletteItem:_4756364_1" class="clearfix divider"><hr></li><li id="paletteItem:_4756365_1" class="clearfix subhead"><h3><span title="INTERAÇÕES">INTERAÇÕES</span></h3></li><li id="paletteItem:_4756355_1" class="clearfix "><a href="/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9341987_1&mode=reset" target="_self"><span title="Fale Com Seu Tutor">Fale Com Seu Tutor</span></a></li><li id="paletteItem:_4756366_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&tool_id=_119_1&tool_type=TOOL&mode=view&mode=reset" target="_self"><span title="Fórum de Discussão">Fórum de Discussão</span></a></li><li id="paletteItem:_4756367_1" class="clearfix "><a href="/webapps/blackboard/content/launchLink.jsp?course_id=_730273_1&tool_id=_133_1&tool_type=TOOL&mode=view&mode=reset" target="_self"><span title="Minhas Notas">Minhas Notas</span></a></li><li id="paletteItem:_4756368_1" class="clearfix divider"><hr></li><li id="paletteItem:_4756369_1" class="clearfix subhead"><h3><span title="INFORMAÇÕES GERAIS">INFORMAÇÕES GERAIS</span></h3></li><li id="paletteItem:_4756356_1" class="clearfix "><a href="/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9341988_1&mode=reset" target="_self"><span title="Suporte Técnico e Labs.">Suporte Técnico e Labs.</span></a></li></ul></div></div>
  </div>
 </div>
 </nav>
 <div role="main" id="contentPanel" class="contentPane  ">
<div class="shadow">
       <div id="editmodeWrapper"> 
 
  <div id="content" class="contentBox ">
   
<div id="pageTitleDiv" class="pageTitle clearfix ">

  
<div id="pageTitleBar" class='pageTitleIcon' tabindex="0">
    <img src="https://learn.content.blackboardcdn.com/3900.10.0-rel.29+3b9a0fc/images/ci/sets/set12/test_on.svg" alt="" id="titleicon"><h1 id="pageTitleHeader" tabindex="-1" ><span id="pageTitleText">
  Iniciar: AS I  </span></h1>
        <span id="_titlebarExtraContent" class="titleButtons"></span>
</div>



</div>

      <div class="container clearfix" id="containerdiv">
    <h2 class="hideoff">Conteúdo</h2>
    <script type="text/javascript" src="/webapps/achievements/js/achievement.js"></script><link rel="stylesheet" href="/webapps/achievements/css/achievements.css" type="text/css" media="screen" /><script type="text/javascript">
new Ajax.Request('/webapps/achievements/checkAchievements.form', {
method:'get',
asynchronous:true,
parameters: {courseId: '_730273_1', type: 1 },
onSuccess: function(response) {
var jsonArray = response.responseJSON;
handleAchievements(jsonArray);
},
onFailure: function() { alert('Something went wrong...'); }
});
</script><script type="text/javascript">
window.document.assessmentBegun = false;
function checkAlreadySubmitted(msg) {
	if(window.document.assessmentBegun == true) {
		alert(msg);
		return false;
	}
	window.document.assessmentBegun = true;
	return true;
 }

function clickOnBegin(){
	if(checkAlreadySubmitted('A ação solicitada está sendo processada. Aguarde a confirmação.'))
		document.location = '/webapps/assessment/take/launch.jsp?course_assessment_id=_640989_1&course_id=_730273_1&content_id=_9342001_1&step=null';
}
function closeWindowOnCancel( newWindow, cancelUrl ){
  if ( "true" === newWindow && window.opener )
  {
    window.close();
  }
  else
  {
    document.location = cancelUrl;
  }
}

function persistDisplayPreference(element, value){
  ClientCache.setItem(element,value);
}

function overrideFilterBlocks( formattedUserName, ipAddress )
{
  AssessmentDWRFacade.overrideFilterBlocks( formattedUserName, ipAddress, '_730273_1', '_640989_1', {
    callback:function(str) {
      if ( str == 'ok' ){
        location.reload(true);
      } else {
        alert(str);
      }
    }
  });
}

function dismissFilterBlocks( formattedUserName, ipAddress )
{
  AssessmentDWRFacade.dismissFilterBlocks( formattedUserName, ipAddress, '_730273_1', '_640989_1', {
    callback:function(str) {
      if ( str == 'ok' ){
        location.reload(true);
      } else {
        alert(str);
      }
    }
  });
}

// reset session data
FastInit.addOnLoad( function()
{
  persistDisplayPreference("instructionsText","inline");


}
);
</script>

<div style='display:none' id="invalidIpAddressLightbox">
	<div class="container clearfix">
     <p class="u_controlsWrapper">Você não está no local correto para fazer este teste</p>
     <p class="u_controlsWrapper">Seu endereço de IP foi gravado como:</p>
     <p class="codeOutput u_centerAlign">177.206.144.169</p>
     <p class="u_controlsWrapper"></p>
	  <div class="u_controlsWrapper u_reverseAlign">
	    <a class="button-4" href="/webapps/blackboard/content/listContent.jsp?content_id=_9341999_1&course_id=_730273_1"> Cancelar</a>
	    <a class="button-4" onclick="javascript:location.reload(true);" href="#"> Tentar novamente</a>
	  </div>
	</div>
</div>


<div id="dataCollectionContainer">
<div class="submitStepTop">
</div>

     <div id="step1" class=" " >
       <h3  id="steptitle1" class="steptitle">
               <span id="stepnumber1">1.</span> &nbsp;
            Instruções
      </h3>     <div id="stepcontent1" class="  stepcontent  " >
   <ol role="presentation">
     
   
     

<li   >
<div class="label">
          Forçar conclusão
    </div>


<div class="field">

  Este teste pode ser salvo e retomado posteriormente.
    <span class="fieldErrorText"></span>
  
</div>
</li> 

<li   >
<div class="label">
          Várias tentativas
    </div>


<div class="field">

  Este teste permite várias tentativas.
    <span class="fieldErrorText"></span>
  
</div>
</li> Clique em <strong>Iniciar</strong> para começar: AS I.  Clique em <strong>Cancelar</strong> para voltar.
   </ol>
  </div>
  
 </div>
 
 		 <div class="submitStepBottom">
<h3 id="steptitle2" class="steptitle submittitle">
 <span id="stepnumber2">2.</span>
 &nbsp;Enviar
</h3>
<p class="taskbuttonhelp">Clique em Iniciar para começar. Clique em Cancelar para sair.</p>

<div class="taskbuttondiv_wrapper">
<p class="taskbuttondiv" id="bottom_submitButtonRow">
			<input  class="button-2" type="button" name="bottom_Cancelar" role="button" value="Cancelar" onclick="document.location='/webapps/blackboard/content/listContent.jsp?content_id=_9341999_1&course_id=_730273_1';">
		<input  class="submit button-1" name="bottom_Iniciar" type="submit" role="button" value="Iniciar" onClick="javascript:clickOnBegin();">

</p>
</div>

</div>
	
</div>

   </div>
   
     </div>
   </div> 
   </div>
   </div>  
</div></div>

  <script type="text/javascript">page.bundle.addKey('inlineconfirmation.close','Fechar');page.bundle.addKey('inlineconfirmation.refresh','Atualizar');page.bundle.addKey('hidden.link.close.menu','Fim do menu. Clique para retornar ao item associado.');page.bundle.addKey('hidden.link.close.form','Fim do formulário. Clique para retornar ao item associado.');page.bundle.addKey('lightbox.loading','Carregando...');page.bundle.addKey('yt.stopped','Interrompido:');page.bundle.addKey('yt.playing','Reproduzindo:');page.bundle.addKey('yt.cued','Marcado:');page.bundle.addKey('yt.buffering','Armazenar em buffer:');page.bundle.addKey('yt.paused','Pausado:');page.bundle.addKey('yt.ended','Finalizado:');page.bundle.addKey('yt.play','Reproduzir');page.bundle.addKey('yt.pause','Pausa');page.bundle.addKey('yt.mute','Mudo');page.bundle.addKey('yt.unmute','Cancelar mudo');page.bundle.addKey('lightbox.overlay','{0} foi aberto como uma página atual de sobreposição de lightbox.');page.bundle.addKey('display.playerControls','Controles do reprodutor');page.bundle.addKey('display.videoPlayerControls','Controles do reprodutor de vídeo');page.bundle.addKey('display.play','Reproduzir');page.bundle.addKey('display.stop','Parar');page.bundle.addKey('display.volumeUp','Aumentar volume');page.bundle.addKey('display.volumeDown','Diminuir volume');page.bundle.addKey('display.mute','Mudo');page.bundle.addKey('display.videoStatus','Status de vídeo');page.bundle.addKey('display.closePlayerControls','Fechar controles do reprodutor');page.bundle.addKey('display.embeddedVideoPlayer','Reprodutor de vídeo incorporado');page.bundle.addKey('display.of','de');page.bundle.addKey('display.view.on.flickr','Exibir foto no Flickr');page.bundle.addKey('mashups.content.data.msg','Não foi possível exibir o conteúdo de Mashup. Isso acontece se o sistema detectar um URL inválido. Remova o item de Mashup e tente novamente para resolver este problema.');page.bundle.addKey('contextmenu.frame.title','Quadro do menu');page.bundle.addKey('frameset.contentframe.title','Conteúdo');page.bundle.addKey('common.pair.paren','{0} ({1})');page.bundle.addKey('coursemenu.show','Mostrar Menu Curso');page.bundle.addKey('coursemenu.hide','Ocultar Menu Curso');page.bundle.addKey('dynamictree.expand','Expandir');page.bundle.addKey('dynamictree.collapse','Recolher');page.bundle.addKey('dynamictree.expand.folder','Expandir {0} árvore de pastas');page.bundle.addKey('dynamictree.collapse.folder','Recolher {0} árvore de pastas');page.bundle.addKey('dragdrop.accessible.error.chooseOption','Selecionar um item primeiro.');page.bundle.addKey('dragdrop.accessible.empty','Nenhum item disponível para reposicionar.');page.bundle.addKey('dragdrop.accessible.complete','Os itens foram reordenados.');page.bundle.addKey('dragdrop.accessible.complete.nochange','Nenhuma alterações de ordem realizada.');page.bundle.addKey('closeStr','Fechar');page.bundle.addKey('moreOptionsStr','Clique para ver opções');page.bundle.addKey('hiddenStr','Este link está oculto aos alunos');page.bundle.addKey('emptyStr','Este link não possui conteúdo');page.bundle.addKey('entryPointChangeConfirmStr','O ponto de entrada foi alterado para o próximo Conteúdo disponível');page.bundle.addKey('subheaderColonStr','Subtítulo: {0}');page.bundle.addKey('confirmQuickEnrollStr','Você receberá a função: {0}. Continuar?');page.bundle.addKey('enterSearchKeyStr','Inserir critérios de pesquisa.');page.bundle.addKey('courseWelcomePageLbTitle','Guia de configuração rápida');page.bundle.addKey('expandCollapse.expand.section.nocolon','Expandir');page.bundle.addKey('expandCollapse.collapse.section.nocolon','Fechar');page.bundle.addKey('expandCollapse.expand.section.param','Expandir {0}');page.bundle.addKey('expandCollapse.collapse.section.param','Recolher {0}');page.bundle.addKey('breadcrumbs.expand','Clique para expandir os caminhos');</script>
  <script type="text/javascript">
   var course_id = "_730273_1";
   var courseTitle = "Lingua Portuguesa - 80h_T12_CICLO_2_21_1";
   var confirmDeleteMenuItemMsg = "Tem certeza de que deseja excluir este item?";
   var confirmQuickUnenrollMsg = "Qualquer dado criado pelo usuário durante a inscrição rápida neste curso será excluído. Continuar?";
   var confirmQuickEnrollMsg = "Você receberá a função: Professor. Continuar?";
   var inNewWindow = false;
   var theCourseMenu;
 </script>
 
  <script type="application/javascript">

      function showTooltip() {
				var tooltipBtn = '<input class="submit tooltipButton" type="submit" role="button"' +
												 'value="Entendi" id="tooltipButton" onclick="removeTooltip()" } />';
				if ( $j( "#ftueTooltip" ) ) {
					if ( $j( "#tooltipButton" ) ) $j( "#tooltipButton" ).remove();
					$j( "#ftueTooltip" ).append( tooltipBtn );
				}

      	if ( $j( ".global-nav-bar-wrap-mobile-nav" ).css('visibility') === 'visible' ) {
					$j( ".global-nav-bar-wrap-mobile-nav" ).prepend( $j( "#ftueTooltip" ) );
				} else {
					$j( "#global-nav" ).append( $j( "#ftueTooltip" ) );
				}
        $j( "#ftueTooltip" ).css('visibility', 'visible');
      }

			function removeTooltip() {
				if ( $j( '#ftueTooltip' ) ) {
					$j( '#ftueTooltip' ).remove();
				}
			}

			function openFtue(title, bodyText, buttonText, redirectUrl) {
				if ( redirectUrl ) {
					var contents = '<div id="ftueLightboxWrapper">' +
												 '<span class="ftueTitle" >' + title + '</span>' +
												 '<img class="ftueImage" src="/images/ci/ftue/AssistPromoModal.png"/>' +
												 '<span class="ftueText" >' + bodyText + '</span>' +
												 '</div>' +
												 '<div id="ftueFooter">' +
												 '<input class="submit ftueButton" type="submit" role="button" ' +
												 'value="' + buttonText + '" onclick=\'window.location="' + redirectUrl + '"\' />' +
												 '</div>';

					var lb = new lightbox.Lightbox(
						{
							lightboxId: 'ftueLightbox',
							contents: contents,
							closeOnBodyClick: false,
							onClose: 'showTooltip()'
						} );
					lb.open();
				}
			}

			
			if ( false )
			{
				var redirect = "/webapps/bb-social-learning-BB5d152e0e8981d/execute/mybb?cmd=display&toolId=LTI_LAUNCH_PLUGIN_____";
				openFtue('Apresenta\xE7\xE3o\x20do\x20Assist', 'O\x20Assist\x20\xE9\x20a\x20central\x20para\x20o\x20sucesso\x20do\x20aluno\x20com\x20recursos\x20do\x20campus\x20e\x20on\x2Dline,\x20dispon\xEDvel\x20para\x20desktop\x20ou\x20dispositivos\x20m\xF3veis\x20no\x20aplicativo\x20da\x20Blackboard.',
					'Explorar\x20o\x20Assist', redirect)
			}

		</script>
	
  <script type="text/javascript">
    page.bundle.addKey('globalnav.menu.expand','Expandir\x20Global\x20Nav');
    page.bundle.addKey('globalnav.menu.collapse','Recolher\x20Global\x20Nav');

    function insertSkipLinkAfterBodyStart(referenceNode, newNode, linkContent)
    {
      if( top === self )
      {
        /* Evaluates if the page is not been loaded inside Iframe,
        only attach skip-link in original view, not Ultra, because ultra has his own skip link. */
        referenceNode.parentNode.insertBefore( newNode, referenceNode );
        newNode.innerHTML = linkContent;
      }
    }

    var skipLink = new Element('a',{id:'skip-to-content', href: '#content', tabIndex: '1'});
    var learnBody = document.body.firstChild;
    var linkContent = 'Pular\x20para\x20o\x20conte\xFAdo';
    this.insertSkipLinkAfterBodyStart(learnBody, skipLink, linkContent);
  </script>
  
  <script type="text/javascript">
    page.bundle.addKey('quick_links.link.title','Navegar\x20para\x20o\x20elemento\x20\x7B1\x7D\x20do\x20tipo\x20\x7B2\x7D\x20em\x20\x7B0\x7D\x20quadro');
    page.bundle.addKey('quick_links.lightbox_title','Links\x20r\xE1pidos');
    page.bundle.addKey('quick_links.link_title','Abrir\x20links\x20r\xE1pidos');
    page.bundle.addKey('quick_links.hotkey.shift','Shift');
    page.bundle.addKey('quick_links.hotkey.control','Ctrl');
    page.bundle.addKey('quick_links.hotkey.alt','Alt');
    page.bundle.addKey('quick_links.hotkey.combination_divider','\x2B');
  </script>
  
  <script type="text/javascript">quickLinks.initialize( [ 'null' ] );</script>
 
   <script type="text/javascript">
   FastInit.addOnLoad( function()
   {
            if ( window.DWREngine )
       {
        try {DWREngine.beginBatch();} catch(ignore) {}
       } 
                page.decoratePageBanner();
                                                             function dataCollRendererInit() {var dccform=$$('div.stepcontent input:visible[type!=hidden], div.stepcontent textarea:visible, div.stepcontent select:visible, div.stepcontent a:visible, div.stepcontent button:visible');if(dccform && dccform.length > 0){dccform[0].focus();}};
                                                             setTimeout(function(){dataCollRendererInit();},100); 
                                                             page.util.initPinBottomSubmitStep();
                                                             page.util.initPinBottomSubmitStep();
                                                             new page.PageHelpToggler(true, 'Ajuda ativada: Clique para ocultar a ajuda da página.', 'Ajuda desabilitada: Clique para mostrar a ajuda da página.', false );
                                                             breadcrumbs.rightMostNavItem = 'null';
                                                             breadcrumbs.rightMostParentURL = '/webapps/blackboard/content/listContent.jsp?course_id=_730273_1&content_id=_9341999_1&mode=reset';
                                                             new page.PageMenuToggler(true,'courseMenuToggle_730273_1', true);
                                                             courseMenu.nonceKey = 'blackboard.platform.security.NonceUtil.nonce.ajax';
                                                             courseMenu.nonceValue = '0f3df06e-cb00-4607-a799-57706eae2910';
                                                             new page.PaletteController('courseMenuPalette', 'courseMenu_link', false, false);
                                                             theCourseMenu = new courseMenu.CourseMenu('/webapps/blackboard/execute/doCourseMenuAction', '/webapps/blackboard/execute/getCourseMenuContextMenu');
                                                             if (typeof(initEditors) == 'function') { initEditors(); }; 
                                                             if (window['org'] && window['org']['owasp']) { org.owasp.esapi.ESAPI.initialize(); }; 
                                                             quickLinks.createHelper();
                                                                  if ( window.DWREngine )
       {
         try {DWREngine.endBatch();} catch(ignore) {}
       }
                          BrowserSpecific.registerListeners();
               });
   </script>
       
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"errorBeacon":"bam-cell.nr-data.net","licenseKey":"232bf20b67","agent":"","beacon":"bam-cell.nr-data.net","applicationTime":111,"applicationID":"379357039","transactionName":"M1NbN0oCDxFYU0JaXAoZahdKFhUReFNCWlwKGVsPWQAKAFZRRFcdE1NbAkgTEkxbXFdQWAZZWBFcTQINTEJFVl4BWExNSxcTF01DGHBcEURKBnUGDxd9WUVDXwVPeABMCg4M","queueTime":0}</script>
</body>
</html>
