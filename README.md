# jso
tracjso
<!DOCTYPE html><html lang="en" class="notranslate" translate="no"><head>
    <!-- needs to be right at the top to prevent Chrome from reloading favicon on every route change -->
    <link rel="icon" type="image/x-icon" href="favicon.png">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="google" content="notranslate">
    <meta name="robots" content="noindex">
    <base href="/">
    <!-- add to homescreen for ios -->
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="default">
    <link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <title>Canada citizenship tracker / Suivi de la citoyenneté canadienne</title>
  <style>@charset "UTF-8";:root{--bs-blue:#0073dd;--bs-indigo:#6610f2;--bs-purple:#6f42c1;--bs-pink:#e83e8c;--bs-red:#dc3545;--bs-orange:#fd7e14;--bs-yellow:#ffc107;--bs-green:#28a745;--bs-teal:#20c997;--bs-cyan:#17a2b8;--bs-black:#000;--bs-white:#fff;--bs-gray:#868e96;--bs-gray-dark:#343a40;--bs-gray-100:#f8f9fa;--bs-gray-200:#e9ecef;--bs-gray-300:#dee2e6;--bs-gray-400:#ced4da;--bs-gray-500:#adb5bd;--bs-gray-600:#868e96;--bs-gray-700:#495057;--bs-gray-800:#343a40;--bs-gray-900:#212529;--bs-primary:#0073dd;--bs-secondary:#868e96;--bs-success:#28a745;--bs-info:#17a2b8;--bs-warning:#ffc107;--bs-danger:#dc3545;--bs-light:#f8f9fa;--bs-dark:#343a40;--bs-primary-rgb:0, 115, 221;--bs-secondary-rgb:134, 142, 150;--bs-success-rgb:40, 167, 69;--bs-info-rgb:23, 162, 184;--bs-warning-rgb:255, 193, 7;--bs-danger-rgb:220, 53, 69;--bs-light-rgb:248, 249, 250;--bs-dark-rgb:52, 58, 64;--bs-white-rgb:255, 255, 255;--bs-black-rgb:0, 0, 0;--bs-body-color-rgb:33, 37, 41;--bs-body-bg-rgb:255, 255, 255;--bs-font-sans-serif:system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", "Noto Sans", "Liberation Sans", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";--bs-font-monospace:SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;--bs-gradient:linear-gradient(180deg, rgba(255, 255, 255, .15), rgba(255, 255, 255, 0));--bs-body-font-family:var(--bs-font-sans-serif);--bs-body-font-size:1rem;--bs-body-font-weight:400;--bs-body-line-height:1.5;--bs-body-color:#212529;--bs-body-bg:#fff;--bs-border-width:1px;--bs-border-style:solid;--bs-border-color:#dee2e6;--bs-border-color-translucent:rgba(0, 0, 0, .175);--bs-border-radius:.375rem;--bs-border-radius-sm:.25rem;--bs-border-radius-lg:.5rem;--bs-border-radius-xl:1rem;--bs-border-radius-2xl:2rem;--bs-border-radius-pill:50rem;--bs-link-color:#0073dd;--bs-link-hover-color:#005cb1;--bs-code-color:#e83e8c;--bs-highlight-bg:#fff3cd}*,*:before,*:after{box-sizing:border-box}@media (prefers-reduced-motion: no-preference){:root{scroll-behavior:smooth}}body{margin:0;font-family:var(--bs-body-font-family);font-size:var(--bs-body-font-size);font-weight:var(--bs-body-font-weight);line-height:var(--bs-body-line-height);color:var(--bs-body-color);text-align:var(--bs-body-text-align);background-color:var(--bs-body-bg);-webkit-text-size-adjust:100%;-webkit-tap-highlight-color:rgba(0,0,0,0)}body{font-family:Noto Sans,sans-serif;font-size:16px;line-height:1.4375;color:#333;background-color:#fff}</style><link rel="stylesheet" href="styles.baee30de8a4b67af.css" media="print" onload="this.media='all'"><noscript><link rel="stylesheet" href="styles.baee30de8a4b67af.css"></noscript></head>
  <body>
    <noscript>
      <style>
        .alert-body-nojs h1 {
          font-size: 22px !important;
          color: #903534;
          font-weight: bold;
        }
        .alert-body-nojs p {
          font-size: 17px !important;
          color: #903534;
        }
        .alert-image-nojs {
          width: 106px;
          background-color: #f1e7e6;
          border: solid 1px #f1e7e6;
          height: 130px;
        }
        .alert-nojs {
          box-shadow: 0 3px 0 0 rgba(178, 178, 178, 0.25);
          border: solid 1px #f1e7e6;
          display: -webkit-box;
          display: -moz-box;
          display: -ms-flexbox;
          display: -webkit-flex;
          display: flex;
          -webkit-box-direction: normal;
          -webkit-box-orient: horizontal;
          -moz-box-direction: normal;
          -moz-box-orient: horizontal;
          -webkit-flex-direction: row;
          -ms-flex-direction: row;
          flex-direction: row;
          -webkit-box-align:center;
          -moz-box-align:center;
          -ms-flex-align:center;
          -webkit-align-items:center;
          align-items:center;
        }
        header{
         margin-top: 32px;
        }
      </style>
      <header>
        <div class="container">
          <div class="row">
            <div class="brand col-md-4 col-sm-6 col-8 col">
              <a href="https://www.canada.ca/en.html" target="_blank">
                <img
                  src="https://wet-boew.github.io/themes-dist/GCWeb/GCWeb/assets/sig-blk-fr.svg"
                  alt="Gouvernment du Canada/ Government of Canada logo"
                />
              </a>
            </div>
          </div>
        </div>
      </header>
      <hr>
      <div class="container mt-4">
        <div class="alert-nojs">
          <div class="alert-image-nojs">
          </div>
          <div class="alert-body-nojs ps-2">
            <h1 class="mt-4"> JavaScript is currently disabled. Please enable it to continue. 
              | JavaScript est actuellement désactivé. Veuillez l’activer pour continuer.
            </h1>
            <p>
              If you don't know how to do this, search for "how to enable JavaScript" to learn how to activate in your browser. 
              | Si vous ne savez pas comment le faire, cherchez « comment activer JavaScript » pour apprendre comment l’activer dans votre navigateur.
            </p>
          </div>
        </div>
      </div>
    </noscript>
    <app-root></app-root>
  <script src="runtime.561befc7b51cdbff.js" type="module"></script><script src="polyfills.2e4b9183ca5e875d.js" type="module"></script><script src="main.8684146fd1e9fb19.js" type="module"></script>

</body></html>
