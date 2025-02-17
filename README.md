# Medical-Image

<!doctype html>
  <html lang="en-US" class="Preview">
    <head>
      <meta name="citation_pii" content="S1361841524003281" />
<meta name="citation_id" content="103403" />
<meta name="citation_issn" content="1361-8415" />
<meta name="citation_volume" content="101" />
<meta name="citation_publisher" content="Elsevier" />
<meta name="citation_firstpage" content="103403" />
<meta name="citation_journal_title" content="Medical Image Analysis" />
<meta name="citation_type" content="JOUR" />
<meta name="citation_doi" content="10.1016/j.media.2024.103403" />
<meta name="dc.identifier" content="10.1016/j.media.2024.103403" />
<meta name="citation_article_type" content="Full-length article" />
<meta property=og:description content="Resting-state functional magnetic resonance imaging (rs-fMRI) provides a non-invasive imaging technique to study patterns of brain activity, and is in…" />
<meta property=og:image content="https://ars.els-cdn.com/content/image/1-s2.0-S1361841524003281-ga1.jpg" />
<meta name="citation_title" content="Self-supervised graph contrastive learning with diffusion augmentation for functional MRI analysis and brain disorder detection" />
<meta property=og:title content="Self-supervised graph contrastive learning with diffusion augmentation for functional MRI analysis and brain disorder detection" />
<meta name="citation_publication_date" content="2025/04/01" />
<meta name="citation_online_date" content="2024/11/29" />
<meta name="robots" content="INDEX,FOLLOW,NOARCHIVE,NOCACHE,NOODP,NOYDIR" />
      <title>Self-supervised graph contrastive learning with diffusion augmentation for functional MRI analysis and brain disorder detection - ScienceDirect</title>
      <link rel="canonical" href="https://www.sciencedirect.com/science/article/abs/pii/S1361841524003281" />
      <meta name="tdm-reservation" content="1">
      <meta name="tdm-policy" content="https://www.elsevier.com/tdm/tdmrep-policy.json">
      <meta property="og:type" content="article" />
      <meta name="viewport" content="initial-scale=1" />
      <meta name="SDTech" content="Proudly brought to you by the SD Technology team" />
      <script type="48d55d7d34a7ef35ff792557-text/javascript">(function newRelicBrowserProSPA() {
  ;
  window.NREUM || (NREUM = {});
  NREUM.init = {
    privacy: {
      cookies_enabled: true
    },
    ajax: {
      deny_list: ["bam-cell.nr-data.net"]
    }
  };
  ;
  NREUM.loader_config = {
    accountID: "2128461",
    trustKey: "2038175",
    agentID: "1118783207",
    licenseKey: "7ac4127487",
    applicationID: "814813181"
  };
  ;
  NREUM.info = {
    beacon: "bam.nr-data.net",
    errorBeacon: "bam.nr-data.net",
    licenseKey: "7ac4127487",
    applicationID: "814813181",
    sa: 1
  };
  ; /*! For license information please see nr-loader-spa-1.238.0.min.js.LICENSE.txt */
  (() => {
    "use strict";

    var e,
      t,
      r = {
        5763: (e, t, r) => {
          r.d(t, {
            P_: () => f,
            Mt: () => p,
            C5: () => s,
            DL: () => v,
            OP: () => T,
            lF: () => D,
            Yu: () => y,
            Dg: () => h,
            CX: () => c,
            GE: () => b,
            sU: () => _
          });
          var n = r(8632),
            i = r(9567);
          const o = {
              beacon: n.ce.beacon,
              errorBeacon: n.ce.errorBeacon,
              licenseKey: void 0,
              applicationID: void 0,
              sa: void 0,
              queueTime: void 0,
              applicationTime: void 0,
              ttGuid: void 0,
              user: void 0,
              account: void 0,
              product: void 0,
              extra: void 0,
              jsAttributes: {},
              userAttributes: void 0,
              atts: void 0,
              transactionName: void 0,
              tNamePlain: void 0
            },
            a = {};
          function s(e) {
            if (!e) throw new Error("All info objects require an agent identifier!");
            if (!a[e]) throw new Error("Info for ".concat(e, " was never set"));
            return a[e];
          }
          function c(e, t) {
            if (!e) throw new Error("All info objects require an agent identifier!");
            a[e] = (0, i.D)(t, o), (0, n.Qy)(e, a[e], "info");
          }
          var u = r(7056);
          const d = () => {
              const e = {
                blockSelector: "[data-nr-block]",
                maskInputOptions: {
                  password: !0
                }
              };
              return {
                allow_bfcache: !0,
                privacy: {
                  cookies_enabled: !0
                },
                ajax: {
                  deny_list: void 0,
                  block_internal: !0,
                  enabled: !0,
                  harvestTimeSeconds: 10
                },
                distributed_tracing: {
                  enabled: void 0,
                  exclude_newrelic_header: void 0,
                  cors_use_newrelic_header: void 0,
                  cors_use_tracecontext_headers: void 0,
                  allowed_origins: void 0
                },
                session: {
                  domain: void 0,
                  expiresMs: u.oD,
                  inactiveMs: u.Hb
                },
                ssl: void 0,
                obfuscate: void 0,
                jserrors: {
                  enabled: !0,
                  harvestTimeSeconds: 10
                },
                metrics: {
                  enabled: !0
                },
                page_action: {
                  enabled: !0,
                  harvestTimeSeconds: 30
                },
                page_view_event: {
                  enabled: !0
                },
                page_view_timing: {
                  enabled: !0,
                  harvestTimeSeconds: 30,
                  long_task: !1
                },
                session_trace: {
                  enabled: !0,
                  harvestTimeSeconds: 10
                },
                harvest: {
                  tooManyRequestsDelay: 60
                },
                session_replay: {
                  enabled: !1,
                  harvestTimeSeconds: 60,
                  sampleRate: .1,
                  errorSampleRate: .1,
                  maskTextSelector: "*",
                  maskAllInputs: !0,
                  get blockClass() {
                    return "nr-block";
                  },
                  get ignoreClass() {
                    return "nr-ignore";
                  },
                  get maskTextClass() {
                    return "nr-mask";
                  },
                  get blockSelector() {
                    return e.blockSelector;
                  },
                  set blockSelector(t) {
                    e.blockSelector += ",".concat(t);
                  },
                  get maskInputOptions() {
                    return e.maskInputOptions;
                  },
                  set maskInputOptions(t) {
                    e.maskInputOptions = {
                      ...t,
                      password: !0
                    };
                  }
                },
                spa: {
                  enabled: !0,
                  harvestTimeSeconds: 10
                }
              };
            },
            l = {};
          function f(e) {
            if (!e) throw new Error("All configuration objects require an agent identifier!");
            if (!l[e]) throw new Error("Configuration for ".concat(e, " was never set"));
            return l[e];
          }
          function h(e, t) {
            if (!e) throw new Error("All configuration objects require an agent identifier!");
            l[e] = (0, i.D)(t, d()), (0, n.Qy)(e, l[e], "config");
          }
          function p(e, t) {
            if (!e) throw new Error("All configuration objects require an agent identifier!");
            var r = f(e);
            if (r) {
              for (var n = t.split("."), i = 0; i < n.length - 1; i++) if ("object" != typeof (r = r[n[i]])) return;
              r = r[n[n.length - 1]];
            }
            return r;
          }
          const g = {
              accountID: void 0,
              trustKey: void 0,
              agentID: void 0,
              licenseKey: void 0,
              applicationID: void 0,
              xpid: void 0
            },
            m = {};
          function v(e) {
            if (!e) throw new Error("All loader-config objects require an agent identifier!");
            if (!m[e]) throw new Error("LoaderConfig for ".concat(e, " was never set"));
            return m[e];
          }
          function b(e, t) {
            if (!e) throw new Error("All loader-config objects require an agent identifier!");
            m[e] = (0, i.D)(t, g), (0, n.Qy)(e, m[e], "loader_config");
          }
          const y = (0, n.mF)().o;
          var w = r(385),
            A = r(6818);
          const x = {
              buildEnv: A.Re,
              bytesSent: {},
              queryBytesSent: {},
              customTransaction: void 0,
              disabled: !1,
              distMethod: A.gF,
              isolatedBacklog: !1,
              loaderType: void 0,
              maxBytes: 3e4,
              offset: Math.floor(w._A?.performance?.timeOrigin || w._A?.performance?.timing?.navigationStart || Date.now()),
              onerror: void 0,
              origin: "" + w._A.location,
              ptid: void 0,
              releaseIds: {},
              session: void 0,
              xhrWrappable: "function" == typeof w._A.XMLHttpRequest?.prototype?.addEventListener,
              version: A.q4,
              denyList: void 0
            },
            E = {};
          function T(e) {
            if (!e) throw new Error("All runtime objects require an agent identifier!");
            if (!E[e]) throw new Error("Runtime for ".concat(e, " was never set"));
            return E[e];
          }
          function _(e, t) {
            if (!e) throw new Error("All runtime objects require an agent identifier!");
            E[e] = (0, i.D)(t, x), (0, n.Qy)(e, E[e], "runtime");
          }
          function D(e) {
            return function (e) {
              try {
                const t = s(e);
                return !!t.licenseKey && !!t.errorBeacon && !!t.applicationID;
              } catch (e) {
                return !1;
              }
            }(e);
          }
        },
        9567: (e, t, r) => {
          r.d(t, {
            D: () => i
          });
          var n = r(50);
          function i(e, t) {
            try {
              if (!e || "object" != typeof e) return (0, n.Z)("Setting a Configurable requires an object as input");
              if (!t || "object" != typeof t) return (0, n.Z)("Setting a Configurable requires a model to set its initial properties");
              const r = Object.create(Object.getPrototypeOf(t), Object.getOwnPropertyDescriptors(t)),
                o = 0 === Object.keys(r).length ? e : r;
              for (let a in o) if (void 0 !== e[a]) try {
                "object" == typeof e[a] && "object" == typeof t[a] ? r[a] = i(e[a], t[a]) : r[a] = e[a];
              } catch (e) {
                (0, n.Z)("An error occurred while setting a property of a Configurable", e);
              }
              return r;
            } catch (e) {
              (0, n.Z)("An error occured while setting a Configurable", e);
            }
          }
        },
        6818: (e, t, r) => {
          r.d(t, {
            Re: () => i,
            gF: () => o,
            q4: () => n
          });
          const n = "1.238.0",
            i = "PROD",
            o = "CDN";
        },
        385: (e, t, r) => {
          r.d(t, {
            FN: () => a,
            IF: () => u,
            Nk: () => l,
            Tt: () => s,
            _A: () => o,
            il: () => n,
            pL: () => c,
            v6: () => i,
            w1: () => d
          });
          const n = "undefined" != typeof window && !!window.document,
            i = "undefined" != typeof WorkerGlobalScope && ("undefined" != typeof self && self instanceof WorkerGlobalScope && self.navigator instanceof WorkerNavigator || "undefined" != typeof globalThis && globalThis instanceof WorkerGlobalScope && globalThis.navigator instanceof WorkerNavigator),
            o = n ? window : "undefined" != typeof WorkerGlobalScope && ("undefined" != typeof self && self instanceof WorkerGlobalScope && self || "undefined" != typeof globalThis && globalThis instanceof WorkerGlobalScope && globalThis),
            a = "" + o?.location,
            s = /iPad|iPhone|iPod/.test(navigator.userAgent),
            c = s && "undefined" == typeof SharedWorker,
            u = (() => {
              const e = navigator.userAgent.match(/Firefox[/\s](\d+\.\d+)/);
              return Array.isArray(e) && e.length >= 2 ? +e[1] : 0;
            })(),
            d = Boolean(n && window.document.documentMode),
            l = !!navigator.sendBeacon;
        },
        1117: (e, t, r) => {
          r.d(t, {
            w: () => o
          });
          var n = r(50);
          const i = {
            agentIdentifier: "",
            ee: void 0
          };
          class o {
            constructor(e) {
              try {
                if ("object" != typeof e) return (0, n.Z)("shared context requires an object as input");
                this.sharedContext = {}, Object.assign(this.sharedContext, i), Object.entries(e).forEach(e => {
                  let [t, r] = e;
                  Object.keys(i).includes(t) && (this.sharedContext[t] = r);
                });
              } catch (e) {
                (0, n.Z)("An error occured while setting SharedContext", e);
              }
            }
          }
        },
        8e3: (e, t, r) => {
          r.d(t, {
            L: () => d,
            R: () => c
          });
          var n = r(8325),
            i = r(1284),
            o = r(4322),
            a = r(3325);
          const s = {};
          function c(e, t) {
            const r = {
              staged: !1,
              priority: a.p[t] || 0
            };
            u(e), s[e].get(t) || s[e].set(t, r);
          }
          function u(e) {
            e && (s[e] || (s[e] = new Map()));
          }
          function d() {
            let e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : "",
              t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "feature";
            if (u(e), !e || !s[e].get(t)) return a(t);
            s[e].get(t).staged = !0;
            const r = [...s[e]];
            function a(t) {
              const r = e ? n.ee.get(e) : n.ee,
                a = o.X.handlers;
              if (r.backlog && a) {
                var s = r.backlog[t],
                  c = a[t];
                if (c) {
                  for (var u = 0; s && u < s.length; ++u) l(s[u], c);
                  (0, i.D)(c, function (e, t) {
                    (0, i.D)(t, function (t, r) {
                      r[0].on(e, r[1]);
                    });
                  });
                }
                delete a[t], r.backlog[t] = null, r.emit("drain-" + t, []);
              }
            }
            r.every(e => {
              let [t, r] = e;
              return r.staged;
            }) && (r.sort((e, t) => e[1].priority - t[1].priority), r.forEach(e => {
              let [t] = e;
              a(t);
            }));
          }
          function l(e, t) {
            var r = e[1];
            (0, i.D)(t[r], function (t, r) {
              var n = e[0];
              if (r[0] === n) {
                var i = r[1],
                  o = e[3],
                  a = e[2];
                i.apply(o, a);
              }
            });
          }
        },
        8325: (e, t, r) => {
          r.d(t, {
            A: () => c,
            ee: () => u
          });
          var n = r(8632),
            i = r(2210),
            o = r(5763);
          class a {
            constructor(e) {
              this.contextId = e;
            }
          }
          var s = r(3117);
          const c = "nr@context:".concat(s.a),
            u = function e(t, r) {
              var n = {},
                s = {},
                d = {},
                f = !1;
              try {
                f = 16 === r.length && (0, o.OP)(r).isolatedBacklog;
              } catch (e) {}
              var h = {
                on: g,
                addEventListener: g,
                removeEventListener: function (e, t) {
                  var r = n[e];
                  if (!r) return;
                  for (var i = 0; i < r.length; i++) r[i] === t && r.splice(i, 1);
                },
                emit: function (e, r, n, i, o) {
                  !1 !== o && (o = !0);
                  if (u.aborted && !i) return;
                  t && o && t.emit(e, r, n);
                  for (var a = p(n), c = m(e), d = c.length, l = 0; l < d; l++) c[l].apply(a, r);
                  var f = b()[s[e]];
                  f && f.push([h, e, r, a]);
                  return a;
                },
                get: v,
                listeners: m,
                context: p,
                buffer: function (e, t) {
                  const r = b();
                  if (t = t || "feature", h.aborted) return;
                  Object.entries(e || {}).forEach(e => {
                    let [n, i] = e;
                    s[i] = t, t in r || (r[t] = []);
                  });
                },
                abort: l,
                aborted: !1,
                isBuffering: function (e) {
                  return !!b()[s[e]];
                },
                debugId: r,
                backlog: f ? {} : t && "object" == typeof t.backlog ? t.backlog : {}
              };
              return h;
              function p(e) {
                return e && e instanceof a ? e : e ? (0, i.X)(e, c, () => new a(c)) : new a(c);
              }
              function g(e, t) {
                n[e] = m(e).concat(t);
              }
              function m(e) {
                return n[e] || [];
              }
              function v(t) {
                return d[t] = d[t] || e(h, t);
              }
              function b() {
                return h.backlog;
              }
            }(void 0, "globalEE"),
            d = (0, n.fP)();
          function l() {
            u.aborted = !0, u.backlog = {};
          }
          d.ee || (d.ee = u);
        },
        5546: (e, t, r) => {
          r.d(t, {
            E: () => n,
            p: () => i
          });
          var n = r(8325).ee.get("handle");
          function i(e, t, r, i, o) {
            o ? (o.buffer([e], i), o.emit(e, t, r)) : (n.buffer([e], i), n.emit(e, t, r));
          }
        },
        4322: (e, t, r) => {
          r.d(t, {
            X: () => o
          });
          var n = r(5546);
          o.on = a;
          var i = o.handlers = {};
          function o(e, t, r, o) {
            a(o || n.E, i, e, t, r);
          }
          function a(e, t, r, i, o) {
            o || (o = "feature"), e || (e = n.E);
            var a = t[o] = t[o] || {};
            (a[r] = a[r] || []).push([e, i]);
          }
        },
        3239: (e, t, r) => {
          r.d(t, {
            bP: () => s,
            iz: () => c,
            m$: () => a
          });
          var n = r(385);
          let i = !1,
            o = !1;
          try {
            const e = {
              get passive() {
                return i = !0, !1;
              },
              get signal() {
                return o = !0, !1;
              }
            };
            n._A.addEventListener("test", null, e), n._A.removeEventListener("test", null, e);
          } catch (e) {}
          function a(e, t) {
            return i || o ? {
              capture: !!e,
              passive: i,
              signal: t
            } : !!e;
          }
          function s(e, t) {
            let r = arguments.length > 2 && void 0 !== arguments[2] && arguments[2],
              n = arguments.length > 3 ? arguments[3] : void 0;
            window.addEventListener(e, t, a(r, n));
          }
          function c(e, t) {
            let r = arguments.length > 2 && void 0 !== arguments[2] && arguments[2],
              n = arguments.length > 3 ? arguments[3] : void 0;
            document.addEventListener(e, t, a(r, n));
          }
        },
        3117: (e, t, r) => {
          r.d(t, {
            a: () => n
          });
          const n = (0, r(4402).Rl)();
        },
        4402: (e, t, r) => {
          r.d(t, {
            Ht: () => u,
            M: () => c,
            Rl: () => a,
            ky: () => s
          });
          var n = r(385);
          const i = "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx";
          function o(e, t) {
            return e ? 15 & e[t] : 16 * Math.random() | 0;
          }
          function a() {
            const e = n._A?.crypto || n._A?.msCrypto;
            let t,
              r = 0;
            return e && e.getRandomValues && (t = e.getRandomValues(new Uint8Array(31))), i.split("").map(e => "x" === e ? o(t, ++r).toString(16) : "y" === e ? (3 & o() | 8).toString(16) : e).join("");
          }
          function s(e) {
            const t = n._A?.crypto || n._A?.msCrypto;
            let r,
              i = 0;
            t && t.getRandomValues && (r = t.getRandomValues(new Uint8Array(31)));
            const a = [];
            for (var s = 0; s < e; s++) a.push(o(r, ++i).toString(16));
            return a.join("");
          }
          function c() {
            return s(16);
          }
          function u() {
            return s(32);
          }
        },
        7056: (e, t, r) => {
          r.d(t, {
            Bq: () => n,
            Hb: () => o,
            oD: () => i
          });
          const n = "NRBA",
            i = 144e5,
            o = 18e5;
        },
        7894: (e, t, r) => {
          function n() {
            return Math.round(performance.now());
          }
          r.d(t, {
            z: () => n
          });
        },
        7243: (e, t, r) => {
          r.d(t, {
            e: () => o
          });
          var n = r(385),
            i = {};
          function o(e) {
            if (e in i) return i[e];
            if (0 === (e || "").indexOf("data:")) return {
              protocol: "data"
            };
            let t;
            var r = n._A?.location,
              o = {};
            if (n.il) t = document.createElement("a"), t.href = e;else try {
              t = new URL(e, r.href);
            } catch (e) {
              return o;
            }
            o.port = t.port;
            var a = t.href.split("://");
            !o.port && a[1] && (o.port = a[1].split("/")[0].split("@").pop().split(":")[1]), o.port && "0" !== o.port || (o.port = "https" === a[0] ? "443" : "80"), o.hostname = t.hostname || r.hostname, o.pathname = t.pathname, o.protocol = a[0], "/" !== o.pathname.charAt(0) && (o.pathname = "/" + o.pathname);
            var s = !t.protocol || ":" === t.protocol || t.protocol === r.protocol,
              c = t.hostname === r.hostname && t.port === r.port;
            return o.sameOrigin = s && (!t.hostname || c), "/" === o.pathname && (i[e] = o), o;
          }
        },
        50: (e, t, r) => {
          function n(e, t) {
            "function" == typeof console.warn && (console.warn("New Relic: ".concat(e)), t && console.warn(t));
          }
          r.d(t, {
            Z: () => n
          });
        },
        2587: (e, t, r) => {
          r.d(t, {
            N: () => c,
            T: () => u
          });
          var n = r(8325),
            i = r(5546),
            o = r(8e3),
            a = r(3325);
          const s = {
            stn: [a.D.sessionTrace],
            err: [a.D.jserrors, a.D.metrics],
            ins: [a.D.pageAction],
            spa: [a.D.spa],
            sr: [a.D.sessionReplay, a.D.sessionTrace]
          };
          function c(e, t) {
            const r = n.ee.get(t);
            e && "object" == typeof e && (Object.entries(e).forEach(e => {
              let [t, n] = e;
              void 0 === u[t] && (s[t] ? s[t].forEach(e => {
                n ? (0, i.p)("feat-" + t, [], void 0, e, r) : (0, i.p)("block-" + t, [], void 0, e, r), (0, i.p)("rumresp-" + t, [Boolean(n)], void 0, e, r);
              }) : n && (0, i.p)("feat-" + t, [], void 0, void 0, r), u[t] = Boolean(n));
            }), Object.keys(s).forEach(e => {
              void 0 === u[e] && (s[e]?.forEach(t => (0, i.p)("rumresp-" + e, [!1], void 0, t, r)), u[e] = !1);
            }), (0, o.L)(t, a.D.pageViewEvent));
          }
          const u = {};
        },
        2210: (e, t, r) => {
          r.d(t, {
            X: () => i
          });
          var n = Object.prototype.hasOwnProperty;
          function i(e, t, r) {
            if (n.call(e, t)) return e[t];
            var i = r();
            if (Object.defineProperty && Object.keys) try {
              return Object.defineProperty(e, t, {
                value: i,
                writable: !0,
                enumerable: !1
              }), i;
            } catch (e) {}
            return e[t] = i, i;
          }
        },
        1284: (e, t, r) => {
          r.d(t, {
            D: () => n
          });
          const n = (e, t) => Object.entries(e || {}).map(e => {
            let [r, n] = e;
            return t(r, n);
          });
        },
        4351: (e, t, r) => {
          r.d(t, {
            P: () => o
          });
          var n = r(8325);
          const i = () => {
            const e = new WeakSet();
            return (t, r) => {
              if ("object" == typeof r && null !== r) {
                if (e.has(r)) return;
                e.add(r);
              }
              return r;
            };
          };
          function o(e) {
            try {
              return JSON.stringify(e, i());
            } catch (e) {
              try {
                n.ee.emit("internal-error", [e]);
              } catch (e) {}
            }
          }
        },
        3960: (e, t, r) => {
          r.d(t, {
            K: () => a,
            b: () => o
          });
          var n = r(3239);
          function i() {
            return "undefined" == typeof document || "complete" === document.readyState;
          }
          function o(e, t) {
            if (i()) return e();
            (0, n.bP)("load", e, t);
          }
          function a(e) {
            if (i()) return e();
            (0, n.iz)("DOMContentLoaded", e);
          }
        },
        8632: (e, t, r) => {
          r.d(t, {
            EZ: () => u,
            Qy: () => c,
            ce: () => o,
            fP: () => a,
            gG: () => d,
            mF: () => s
          });
          var n = r(7894),
            i = r(385);
          const o = {
            beacon: "bam.nr-data.net",
            errorBeacon: "bam.nr-data.net"
          };
          function a() {
            return i._A.NREUM || (i._A.NREUM = {}), void 0 === i._A.newrelic && (i._A.newrelic = i._A.NREUM), i._A.NREUM;
          }
          function s() {
            let e = a();
            return e.o || (e.o = {
              ST: i._A.setTimeout,
              SI: i._A.setImmediate,
              CT: i._A.clearTimeout,
              XHR: i._A.XMLHttpRequest,
              REQ: i._A.Request,
              EV: i._A.Event,
              PR: i._A.Promise,
              MO: i._A.MutationObserver,
              FETCH: i._A.fetch
            }), e;
          }
          function c(e, t, r) {
            let i = a();
            const o = i.initializedAgents || {},
              s = o[e] || {};
            return Object.keys(s).length || (s.initializedAt = {
              ms: (0, n.z)(),
              date: new Date()
            }), i.initializedAgents = {
              ...o,
              [e]: {
                ...s,
                [r]: t
              }
            }, i;
          }
          function u(e, t) {
            a()[e] = t;
          }
          function d() {
            return function () {
              let e = a();
              const t = e.info || {};
              e.info = {
                beacon: o.beacon,
                errorBeacon: o.errorBeacon,
                ...t
              };
            }(), function () {
              let e = a();
              const t = e.init || {};
              e.init = {
                ...t
              };
            }(), s(), function () {
              let e = a();
              const t = e.loader_config || {};
              e.loader_config = {
                ...t
              };
            }(), a();
          }
        },
        7956: (e, t, r) => {
          r.d(t, {
            N: () => i
          });
          var n = r(3239);
          function i(e) {
            let t = arguments.length > 1 && void 0 !== arguments[1] && arguments[1],
              r = arguments.length > 2 ? arguments[2] : void 0,
              i = arguments.length > 3 ? arguments[3] : void 0;
            return void (0, n.iz)("visibilitychange", function () {
              if (t) return void ("hidden" == document.visibilityState && e());
              e(document.visibilityState);
            }, r, i);
          }
        },
        1214: (e, t, r) => {
          r.d(t, {
            em: () => b,
            u5: () => j,
            QU: () => O,
            _L: () => I,
            Gm: () => H,
            Lg: () => L,
            BV: () => G,
            Kf: () => K
          });
          var n = r(8325),
            i = r(3117);
          const o = "nr@original:".concat(i.a);
          var a = Object.prototype.hasOwnProperty,
            s = !1;
          function c(e, t) {
            return e || (e = n.ee), r.inPlace = function (e, t, n, i, o) {
              n || (n = "");
              const a = "-" === n.charAt(0);
              for (let s = 0; s < t.length; s++) {
                const c = t[s],
                  u = e[c];
                d(u) || (e[c] = r(u, a ? c + n : n, i, c, o));
              }
            }, r.flag = o, r;
            function r(t, r, n, s, c) {
              return d(t) ? t : (r || (r = ""), nrWrapper[o] = t, function (e, t, r) {
                if (Object.defineProperty && Object.keys) try {
                  return Object.keys(e).forEach(function (r) {
                    Object.defineProperty(t, r, {
                      get: function () {
                        return e[r];
                      },
                      set: function (t) {
                        return e[r] = t, t;
                      }
                    });
                  }), t;
                } catch (e) {
                  u([e], r);
                }
                for (var n in e) a.call(e, n) && (t[n] = e[n]);
              }(t, nrWrapper, e), nrWrapper);
              function nrWrapper() {
                var o, a, d, l;
                try {
                  a = this, o = [...arguments], d = "function" == typeof n ? n(o, a) : n || {};
                } catch (t) {
                  u([t, "", [o, a, s], d], e);
                }
                i(r + "start", [o, a, s], d, c);
                try {
                  return l = t.apply(a, o);
                } catch (e) {
                  throw i(r + "err", [o, a, e], d, c), e;
                } finally {
                  i(r + "end", [o, a, l], d, c);
                }
              }
            }
            function i(r, n, i, o) {
              if (!s || t) {
                var a = s;
                s = !0;
                try {
                  e.emit(r, n, i, t, o);
                } catch (t) {
                  u([t, r, n, i], e);
                }
                s = a;
              }
            }
          }
          function u(e, t) {
            t || (t = n.ee);
            try {
              t.emit("internal-error", e);
            } catch (e) {}
          }
          function d(e) {
            return !(e && e instanceof Function && e.apply && !e[o]);
          }
          var l = r(2210),
            f = r(385);
          const h = {},
            p = f._A.XMLHttpRequest,
            g = "addEventListener",
            m = "removeEventListener",
            v = "nr@wrapped:".concat(n.A);
          function b(e) {
            var t = function (e) {
              return (e || n.ee).get("events");
            }(e);
            if (h[t.debugId]++) return t;
            h[t.debugId] = 1;
            var r = c(t, !0);
            function i(e) {
              r.inPlace(e, [g, m], "-", o);
            }
            function o(e, t) {
              return e[1];
            }
            return "getPrototypeOf" in Object && (f.il && y(document, i), y(f._A, i), y(p.prototype, i)), t.on(g + "-start", function (e, t) {
              var n = e[1];
              if (null !== n && ("function" == typeof n || "object" == typeof n)) {
                var i = (0, l.X)(n, v, function () {
                  var e = {
                    object: function () {
                      if ("function" != typeof n.handleEvent) return;
                      return n.handleEvent.apply(n, arguments);
                    },
                    function: n
                  }[typeof n];
                  return e ? r(e, "fn-", null, e.name || "anonymous") : n;
                });
                this.wrapped = e[1] = i;
              }
            }), t.on(m + "-start", function (e) {
              e[1] = this.wrapped || e[1];
            }), t;
          }
          function y(e, t) {
            let r = e;
            for (; "object" == typeof r && !Object.prototype.hasOwnProperty.call(r, g);) r = Object.getPrototypeOf(r);
            for (var n = arguments.length, i = new Array(n > 2 ? n - 2 : 0), o = 2; o < n; o++) i[o - 2] = arguments[o];
            r && t(r, ...i);
          }
          var w = "fetch-",
            A = w + "body-",
            x = ["arrayBuffer", "blob", "json", "text", "formData"],
            E = f._A.Request,
            T = f._A.Response,
            _ = "prototype";
          const D = {};
          function j(e) {
            const t = function (e) {
              return (e || n.ee).get("fetch");
            }(e);
            if (!(E && T && f._A.fetch)) return t;
            if (D[t.debugId]++) return t;
            function r(e, r, i) {
              var o = e[r];
              "function" == typeof o && (e[r] = function () {
                var e,
                  r = [...arguments],
                  a = {};
                t.emit(i + "before-start", [r], a), a[n.A] && a[n.A].dt && (e = a[n.A].dt);
                var s = o.apply(this, r);
                return t.emit(i + "start", [r, e], s), s.then(function (e) {
                  return t.emit(i + "end", [null, e], s), e;
                }, function (e) {
                  throw t.emit(i + "end", [e], s), e;
                });
              });
            }
            return D[t.debugId] = 1, x.forEach(e => {
              r(E[_], e, A), r(T[_], e, A);
            }), r(f._A, "fetch", w), t.on(w + "end", function (e, r) {
              var n = this;
              if (r) {
                var i = r.headers.get("content-length");
                null !== i && (n.rxSize = i), t.emit(w + "done", [null, r], n);
              } else t.emit(w + "done", [e], n);
            }), t;
          }
          const C = {},
            N = ["pushState", "replaceState"];
          function O(e) {
            const t = function (e) {
              return (e || n.ee).get("history");
            }(e);
            return !f.il || C[t.debugId]++ || (C[t.debugId] = 1, c(t).inPlace(window.history, N, "-")), t;
          }
          var S = r(3239);
          const P = {},
            R = ["appendChild", "insertBefore", "replaceChild"];
          function I(e) {
            const t = function (e) {
              return (e || n.ee).get("jsonp");
            }(e);
            if (!f.il || P[t.debugId]) return t;
            P[t.debugId] = !0;
            var r = c(t),
              i = /[?&](?:callback|cb)=([^&#]+)/,
              o = /(.*)\.([^.]+)/,
              a = /^(\w+)(\.|$)(.*)$/;
            function s(e, t) {
              if (!e) return t;
              const r = e.match(a),
                n = r[1];
              return s(r[3], t[n]);
            }
            return r.inPlace(Node.prototype, R, "dom-"), t.on("dom-start", function (e) {
              !function (e) {
                if (!e || "string" != typeof e.nodeName || "script" !== e.nodeName.toLowerCase()) return;
                if ("function" != typeof e.addEventListener) return;
                var n = (a = e.src, c = a.match(i), c ? c[1] : null);
                var a, c;
                if (!n) return;
                var u = function (e) {
                  var t = e.match(o);
                  if (t && t.length >= 3) return {
                    key: t[2],
                    parent: s(t[1], window)
                  };
                  return {
                    key: e,
                    parent: window
                  };
                }(n);
                if ("function" != typeof u.parent[u.key]) return;
                var d = {};
                function l() {
                  t.emit("jsonp-end", [], d), e.removeEventListener("load", l, (0, S.m$)(!1)), e.removeEventListener("error", f, (0, S.m$)(!1));
                }
                function f() {
                  t.emit("jsonp-error", [], d), t.emit("jsonp-end", [], d), e.removeEventListener("load", l, (0, S.m$)(!1)), e.removeEventListener("error", f, (0, S.m$)(!1));
                }
                r.inPlace(u.parent, [u.key], "cb-", d), e.addEventListener("load", l, (0, S.m$)(!1)), e.addEventListener("error", f, (0, S.m$)(!1)), t.emit("new-jsonp", [e.src], d);
              }(e[0]);
            }), t;
          }
          const k = {};
          function H(e) {
            const t = function (e) {
              return (e || n.ee).get("mutation");
            }(e);
            if (!f.il || k[t.debugId]) return t;
            k[t.debugId] = !0;
            var r = c(t),
              i = f._A.MutationObserver;
            return i && (window.MutationObserver = function (e) {
              return this instanceof i ? new i(r(e, "fn-")) : i.apply(this, arguments);
            }, MutationObserver.prototype = i.prototype), t;
          }
          const z = {};
          function L(e) {
            const t = function (e) {
              return (e || n.ee).get("promise");
            }(e);
            if (z[t.debugId]) return t;
            z[t.debugId] = !0;
            var r = t.context,
              i = c(t),
              a = f._A.Promise;
            return a && function () {
              function e(r) {
                var n = t.context(),
                  o = i(r, "executor-", n, null, !1);
                const s = Reflect.construct(a, [o], e);
                return t.context(s).getCtx = function () {
                  return n;
                }, s;
              }
              f._A.Promise = e, Object.defineProperty(e, "name", {
                value: "Promise"
              }), e.toString = function () {
                return a.toString();
              }, Object.setPrototypeOf(e, a), ["all", "race"].forEach(function (r) {
                const n = a[r];
                e[r] = function (e) {
                  let i = !1;
                  [...(e || [])].forEach(e => {
                    this.resolve(e).then(a("all" === r), a(!1));
                  });
                  const o = n.apply(this, arguments);
                  return o;
                  function a(e) {
                    return function () {
                      t.emit("propagate", [null, !i], o, !1, !1), i = i || !e;
                    };
                  }
                };
              }), ["resolve", "reject"].forEach(function (r) {
                const n = a[r];
                e[r] = function (e) {
                  const r = n.apply(this, arguments);
                  return e !== r && t.emit("propagate", [e, !0], r, !1, !1), r;
                };
              }), e.prototype = a.prototype;
              const n = a.prototype.then;
              a.prototype.then = function () {
                var e = this,
                  o = r(e);
                o.promise = e;
                for (var a = arguments.length, s = new Array(a), c = 0; c < a; c++) s[c] = arguments[c];
                s[0] = i(s[0], "cb-", o, null, !1), s[1] = i(s[1], "cb-", o, null, !1);
                const u = n.apply(this, s);
                return o.nextPromise = u, t.emit("propagate", [e, !0], u, !1, !1), u;
              }, a.prototype.then[o] = n, t.on("executor-start", function (e) {
                e[0] = i(e[0], "resolve-", this, null, !1), e[1] = i(e[1], "resolve-", this, null, !1);
              }), t.on("executor-err", function (e, t, r) {
                e[1](r);
              }), t.on("cb-end", function (e, r, n) {
                t.emit("propagate", [n, !0], this.nextPromise, !1, !1);
              }), t.on("propagate", function (e, r, n) {
                this.getCtx && !r || (this.getCtx = function () {
                  if (e instanceof Promise) var r = t.context(e);
                  return r && r.getCtx ? r.getCtx() : this;
                });
              });
            }(), t;
          }
          const M = {},
            B = "setTimeout",
            F = "setInterval",
            U = "clearTimeout",
            q = "-start",
            Z = "-",
            V = [B, "setImmediate", F, U, "clearImmediate"];
          function G(e) {
            const t = function (e) {
              return (e || n.ee).get("timer");
            }(e);
            if (M[t.debugId]++) return t;
            M[t.debugId] = 1;
            var r = c(t);
            return r.inPlace(f._A, V.slice(0, 2), B + Z), r.inPlace(f._A, V.slice(2, 3), F + Z), r.inPlace(f._A, V.slice(3), U + Z), t.on(F + q, function (e, t, n) {
              e[0] = r(e[0], "fn-", null, n);
            }), t.on(B + q, function (e, t, n) {
              this.method = n, this.timerDuration = isNaN(e[1]) ? 0 : +e[1], e[0] = r(e[0], "fn-", this, n);
            }), t;
          }
          var W = r(50);
          const X = {},
            Q = ["open", "send"];
          function K(e) {
            var t = e || n.ee;
            const r = function (e) {
              return (e || n.ee).get("xhr");
            }(t);
            if (X[r.debugId]++) return r;
            X[r.debugId] = 1, b(t);
            var i = c(r),
              o = f._A.XMLHttpRequest,
              a = f._A.MutationObserver,
              s = f._A.Promise,
              u = f._A.setInterval,
              d = "readystatechange",
              l = ["onload", "onerror", "onabort", "onloadstart", "onloadend", "onprogress", "ontimeout"],
              h = [],
              p = f._A.XMLHttpRequest = function (e) {
                const t = new o(e),
                  n = r.context(t);
                try {
                  r.emit("new-xhr", [t], n), t.addEventListener(d, (a = n, function () {
                    var e = this;
                    e.readyState > 3 && !a.resolved && (a.resolved = !0, r.emit("xhr-resolved", [], e)), i.inPlace(e, l, "fn-", A);
                  }), (0, S.m$)(!1));
                } catch (e) {
                  (0, W.Z)("An error occurred while intercepting XHR", e);
                  try {
                    r.emit("internal-error", [e]);
                  } catch (e) {}
                }
                var a;
                return t;
              };
            function g(e, t) {
              i.inPlace(t, ["onreadystatechange"], "fn-", A);
            }
            if (function (e, t) {
              for (var r in e) t[r] = e[r];
            }(o, p), p.prototype = o.prototype, i.inPlace(p.prototype, Q, "-xhr-", A), r.on("send-xhr-start", function (e, t) {
              g(e, t), function (e) {
                h.push(e), a && (m ? m.then(w) : u ? u(w) : (v = -v, y.data = v));
              }(t);
            }), r.on("open-xhr-start", g), a) {
              var m = s && s.resolve();
              if (!u && !s) {
                var v = 1,
                  y = document.createTextNode(v);
                new a(w).observe(y, {
                  characterData: !0
                });
              }
            } else t.on("fn-end", function (e) {
              e[0] && e[0].type === d || w();
            });
            function w() {
              for (var e = 0; e < h.length; e++) g(0, h[e]);
              h.length && (h = []);
            }
            function A(e, t) {
              return t;
            }
            return r;
          }
        },
        7825: (e, t, r) => {
          r.d(t, {
            t: () => n
          });
          const n = r(3325).D.ajax;
        },
        6660: (e, t, r) => {
          r.d(t, {
            t: () => n
          });
          const n = r(3325).D.jserrors;
        },
        3081: (e, t, r) => {
          r.d(t, {
            gF: () => o,
            mY: () => i,
            t9: () => n,
            vz: () => s,
            xS: () => a
          });
          const n = r(3325).D.metrics,
            i = "sm",
            o = "cm",
            a = "storeSupportabilityMetrics",
            s = "storeEventMetrics";
        },
        4649: (e, t, r) => {
          r.d(t, {
            t: () => n
          });
          const n = r(3325).D.pageAction;
        },
        7633: (e, t, r) => {
          r.d(t, {
            Dz: () => i,
            OJ: () => a,
            qw: () => o,
            t9: () => n
          });
          const n = r(3325).D.pageViewEvent,
            i = "firstbyte",
            o = "domcontent",
            a = "windowload";
        },
        9251: (e, t, r) => {
          r.d(t, {
            t: () => n
          });
          const n = r(3325).D.pageViewTiming;
        },
        3614: (e, t, r) => {
          r.d(t, {
            BST_RESOURCE: () => i,
            END: () => s,
            FEATURE_NAME: () => n,
            FN_END: () => u,
            FN_START: () => c,
            PUSH_STATE: () => d,
            RESOURCE: () => o,
            START: () => a
          });
          const n = r(3325).D.sessionTrace,
            i = "bstResource",
            o = "resource",
            a = "-start",
            s = "-end",
            c = "fn" + a,
            u = "fn" + s,
            d = "pushState";
        },
        7836: (e, t, r) => {
          r.d(t, {
            BODY: () => x,
            CB_END: () => E,
            CB_START: () => u,
            END: () => A,
            FEATURE_NAME: () => i,
            FETCH: () => _,
            FETCH_BODY: () => v,
            FETCH_DONE: () => m,
            FETCH_START: () => g,
            FN_END: () => c,
            FN_START: () => s,
            INTERACTION: () => f,
            INTERACTION_API: () => d,
            INTERACTION_EVENTS: () => o,
            JSONP_END: () => b,
            JSONP_NODE: () => p,
            JS_TIME: () => T,
            MAX_TIMER_BUDGET: () => a,
            REMAINING: () => l,
            SPA_NODE: () => h,
            START: () => w,
            originalSetTimeout: () => y
          });
          var n = r(5763);
          const i = r(3325).D.spa,
            o = ["click", "submit", "keypress", "keydown", "keyup", "change"],
            a = 999,
            s = "fn-start",
            c = "fn-end",
            u = "cb-start",
            d = "api-ixn-",
            l = "remaining",
            f = "interaction",
            h = "spaNode",
            p = "jsonpNode",
            g = "fetch-start",
            m = "fetch-done",
            v = "fetch-body-",
            b = "jsonp-end",
            y = n.Yu.ST,
            w = "-start",
            A = "-end",
            x = "-body",
            E = "cb" + A,
            T = "jsTime",
            _ = "fetch";
        },
        5938: (e, t, r) => {
          r.d(t, {
            W: () => o
          });
          var n = r(5763),
            i = r(8325);
          class o {
            constructor(e, t, r) {
              this.agentIdentifier = e, this.aggregator = t, this.ee = i.ee.get(e, (0, n.OP)(this.agentIdentifier).isolatedBacklog), this.featureName = r, this.blocked = !1;
            }
          }
        },
        9144: (e, t, r) => {
          r.d(t, {
            j: () => m
          });
          var n = r(3325),
            i = r(5763),
            o = r(5546),
            a = r(8325),
            s = r(7894),
            c = r(8e3),
            u = r(3960),
            d = r(385),
            l = r(50),
            f = r(3081),
            h = r(8632);
          function p() {
            const e = (0, h.gG)();
            ["setErrorHandler", "finished", "addToTrace", "inlineHit", "addRelease", "addPageAction", "setCurrentRouteName", "setPageViewName", "setCustomAttribute", "interaction", "noticeError", "setUserId", "setApplicationVersion"].forEach(t => {
              e[t] = function () {
                for (var r = arguments.length, n = new Array(r), i = 0; i < r; i++) n[i] = arguments[i];
                return function (t) {
                  for (var r = arguments.length, n = new Array(r > 1 ? r - 1 : 0), i = 1; i < r; i++) n[i - 1] = arguments[i];
                  let o = [];
                  return Object.values(e.initializedAgents).forEach(e => {
                    e.exposed && e.api[t] && o.push(e.api[t](...n));
                  }), o.length > 1 ? o : o[0];
                }(t, ...n);
              };
            });
          }
          var g = r(2587);
          function m(e) {
            let t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {},
              m = arguments.length > 2 ? arguments[2] : void 0,
              v = arguments.length > 3 ? arguments[3] : void 0,
              {
                init: b,
                info: y,
                loader_config: w,
                runtime: A = {
                  loaderType: m
                },
                exposed: x = !0
              } = t;
            const E = (0, h.gG)();
            y || (b = E.init, y = E.info, w = E.loader_config), (0, i.Dg)(e, b || {}), (0, i.GE)(e, w || {}), y.jsAttributes ??= {}, d.v6 && (y.jsAttributes.isWorker = !0), (0, i.CX)(e, y);
            const T = (0, i.P_)(e);
            A.denyList = [...(T.ajax?.deny_list || []), ...(T.ajax?.block_internal ? [y.beacon, y.errorBeacon] : [])], (0, i.sU)(e, A), p();
            const _ = function (e, t) {
              t || (0, c.R)(e, "api");
              const h = {};
              var p = a.ee.get(e),
                g = p.get("tracer"),
                m = "api-",
                v = m + "ixn-";
              function b(t, r, n, o) {
                const a = (0, i.C5)(e);
                return null === r ? delete a.jsAttributes[t] : (0, i.CX)(e, {
                  ...a,
                  jsAttributes: {
                    ...a.jsAttributes,
                    [t]: r
                  }
                }), A(m, n, !0, o || null === r ? "session" : void 0)(t, r);
              }
              function y() {}
              ["setErrorHandler", "finished", "addToTrace", "inlineHit", "addRelease"].forEach(e => h[e] = A(m, e, !0, "api")), h.addPageAction = A(m, "addPageAction", !0, n.D.pageAction), h.setCurrentRouteName = A(m, "routeName", !0, n.D.spa), h.setPageViewName = function (t, r) {
                if ("string" == typeof t) return "/" !== t.charAt(0) && (t = "/" + t), (0, i.OP)(e).customTransaction = (r || "http://custom.transaction") + t, A(m, "setPageViewName", !0)();
              }, h.setCustomAttribute = function (e, t) {
                let r = arguments.length > 2 && void 0 !== arguments[2] && arguments[2];
                if ("string" == typeof e) {
                  if (["string", "number"].includes(typeof t) || null === t) return b(e, t, "setCustomAttribute", r);
                  (0, l.Z)("Failed to execute setCustomAttribute.\nNon-null value must be a string or number type, but a type of <".concat(typeof t, "> was provided."));
                } else (0, l.Z)("Failed to execute setCustomAttribute.\nName must be a string type, but a type of <".concat(typeof e, "> was provided."));
              }, h.setUserId = function (e) {
                if ("string" == typeof e || null === e) return b("enduser.id", e, "setUserId", !0);
                (0, l.Z)("Failed to execute setUserId.\nNon-null value must be a string type, but a type of <".concat(typeof e, "> was provided."));
              }, h.setApplicationVersion = function (e) {
                if ("string" == typeof e || null === e) return b("application.version", e, "setApplicationVersion", !1);
                (0, l.Z)("Failed to execute setApplicationVersion. Expected <String | null>, but got <".concat(typeof e, ">."));
              }, h.interaction = function () {
                return new y().get();
              };
              var w = y.prototype = {
                createTracer: function (e, t) {
                  var r = {},
                    i = this,
                    a = "function" == typeof t;
                  return (0, o.p)(v + "tracer", [(0, s.z)(), e, r], i, n.D.spa, p), function () {
                    if (g.emit((a ? "" : "no-") + "fn-start", [(0, s.z)(), i, a], r), a) try {
                      return t.apply(this, arguments);
                    } catch (e) {
                      throw g.emit("fn-err", [arguments, this, e], r), e;
                    } finally {
                      g.emit("fn-end", [(0, s.z)()], r);
                    }
                  };
                }
              };
              function A(e, t, r, i) {
                return function () {
                  return (0, o.p)(f.xS, ["API/" + t + "/called"], void 0, n.D.metrics, p), i && (0, o.p)(e + t, [(0, s.z)(), ...arguments], r ? null : this, i, p), r ? void 0 : this;
                };
              }
              function x() {
                r.e(111).then(r.bind(r, 7438)).then(t => {
                  let {
                    setAPI: r
                  } = t;
                  r(e), (0, c.L)(e, "api");
                }).catch(() => (0, l.Z)("Downloading runtime APIs failed..."));
              }
              return ["actionText", "setName", "setAttribute", "save", "ignore", "onEnd", "getContext", "end", "get"].forEach(e => {
                w[e] = A(v, e, void 0, n.D.spa);
              }), h.noticeError = function (e, t) {
                "string" == typeof e && (e = new Error(e)), (0, o.p)(f.xS, ["API/noticeError/called"], void 0, n.D.metrics, p), (0, o.p)("err", [e, (0, s.z)(), !1, t], void 0, n.D.jserrors, p);
              }, d.il ? (0, u.b)(() => x(), !0) : x(), h;
            }(e, v);
            return (0, h.Qy)(e, _, "api"), (0, h.Qy)(e, x, "exposed"), (0, h.EZ)("activatedFeatures", g.T), _;
          }
        },
        3325: (e, t, r) => {
          r.d(t, {
            D: () => n,
            p: () => i
          });
          const n = {
              ajax: "ajax",
              jserrors: "jserrors",
              metrics: "metrics",
              pageAction: "page_action",
              pageViewEvent: "page_view_event",
              pageViewTiming: "page_view_timing",
              sessionReplay: "session_replay",
              sessionTrace: "session_trace",
              spa: "spa"
            },
            i = {
              [n.pageViewEvent]: 1,
              [n.pageViewTiming]: 2,
              [n.metrics]: 3,
              [n.jserrors]: 4,
              [n.ajax]: 5,
              [n.sessionTrace]: 6,
              [n.pageAction]: 7,
              [n.spa]: 8,
              [n.sessionReplay]: 9
            };
        }
      },
      n = {};
    function i(e) {
      var t = n[e];
      if (void 0 !== t) return t.exports;
      var o = n[e] = {
        exports: {}
      };
      return r[e](o, o.exports, i), o.exports;
    }
    i.m = r, i.d = (e, t) => {
      for (var r in t) i.o(t, r) && !i.o(e, r) && Object.defineProperty(e, r, {
        enumerable: !0,
        get: t[r]
      });
    }, i.f = {}, i.e = e => Promise.all(Object.keys(i.f).reduce((t, r) => (i.f[r](e, t), t), [])), i.u = e => "nr-spa.1097a448-1.238.0.min.js", i.o = (e, t) => Object.prototype.hasOwnProperty.call(e, t), e = {}, t = "NRBA-1.238.0.PROD:", i.l = (r, n, o, a) => {
      if (e[r]) e[r].push(n);else {
        var s, c;
        if (void 0 !== o) for (var u = document.getElementsByTagName("script"), d = 0; d < u.length; d++) {
          var l = u[d];
          if (l.getAttribute("src") == r || l.getAttribute("data-webpack") == t + o) {
            s = l;
            break;
          }
        }
        s || (c = !0, (s = document.createElement("script")).charset = "utf-8", s.timeout = 120, i.nc && s.setAttribute("nonce", i.nc), s.setAttribute("data-webpack", t + o), s.src = r), e[r] = [n];
        var f = (t, n) => {
            s.onerror = s.onload = null, clearTimeout(h);
            var i = e[r];
            if (delete e[r], s.parentNode && s.parentNode.removeChild(s), i && i.forEach(e => e(n)), t) return t(n);
          },
          h = setTimeout(f.bind(null, void 0, {
            type: "timeout",
            target: s
          }), 12e4);
        s.onerror = f.bind(null, s.onerror), s.onload = f.bind(null, s.onload), c && document.head.appendChild(s);
      }
    }, i.r = e => {
      "undefined" != typeof Symbol && Symbol.toStringTag && Object.defineProperty(e, Symbol.toStringTag, {
        value: "Module"
      }), Object.defineProperty(e, "__esModule", {
        value: !0
      });
    }, i.p = "https://js-agent.newrelic.com/", (() => {
      var e = {
        801: 0,
        92: 0
      };
      i.f.j = (t, r) => {
        var n = i.o(e, t) ? e[t] : void 0;
        if (0 !== n) if (n) r.push(n[2]);else {
          var o = new Promise((r, i) => n = e[t] = [r, i]);
          r.push(n[2] = o);
          var a = i.p + i.u(t),
            s = new Error();
          i.l(a, r => {
            if (i.o(e, t) && (0 !== (n = e[t]) && (e[t] = void 0), n)) {
              var o = r && ("load" === r.type ? "missing" : r.type),
                a = r && r.target && r.target.src;
              s.message = "Loading chunk " + t + " failed.\n(" + o + ": " + a + ")", s.name = "ChunkLoadError", s.type = o, s.request = a, n[1](s);
            }
          }, "chunk-" + t, t);
        }
      };
      var t = (t, r) => {
          var n,
            o,
            [a, s, c] = r,
            u = 0;
          if (a.some(t => 0 !== e[t])) {
            for (n in s) i.o(s, n) && (i.m[n] = s[n]);
            if (c) c(i);
          }
          for (t && t(r); u < a.length; u++) o = a[u], i.o(e, o) && e[o] && e[o][0](), e[o] = 0;
        },
        r = self["webpackChunk:NRBA-1.238.0.PROD"] = self["webpackChunk:NRBA-1.238.0.PROD"] || [];
      r.forEach(t.bind(null, 0)), r.push = t.bind(null, r.push.bind(r));
    })(), (() => {
      var e = i(50);
      class t {
        addPageAction(t, r) {
          (0, e.Z)("Call to agent api addPageAction failed. The session trace feature is not currently initialized.");
        }
        setPageViewName(t, r) {
          (0, e.Z)("Call to agent api setPageViewName failed. The page view feature is not currently initialized.");
        }
        setCustomAttribute(t, r, n) {
          (0, e.Z)("Call to agent api setCustomAttribute failed. The js errors feature is not currently initialized.");
        }
        noticeError(t, r) {
          (0, e.Z)("Call to agent api noticeError failed. The js errors feature is not currently initialized.");
        }
        setUserId(t) {
          (0, e.Z)("Call to agent api setUserId failed. The js errors feature is not currently initialized.");
        }
        setApplicationVersion(t) {
          (0, e.Z)("Call to agent api setApplicationVersion failed. The agent is not currently initialized.");
        }
        setErrorHandler(t) {
          (0, e.Z)("Call to agent api setErrorHandler failed. The js errors feature is not currently initialized.");
        }
        finished(t) {
          (0, e.Z)("Call to agent api finished failed. The page action feature is not currently initialized.");
        }
        addRelease(t, r) {
          (0, e.Z)("Call to agent api addRelease failed. The agent is not currently initialized.");
        }
      }
      var r = i(3325),
        n = i(5763);
      const o = Object.values(r.D);
      function a(e) {
        const t = {};
        return o.forEach(r => {
          t[r] = function (e, t) {
            return !1 !== (0, n.Mt)(t, "".concat(e, ".enabled"));
          }(r, e);
        }), t;
      }
      var s = i(9144);
      var c = i(5546),
        u = i(385),
        d = i(8e3),
        l = i(5938),
        f = i(3960);
      class h extends l.W {
        constructor(e, t, r) {
          let n = !(arguments.length > 3 && void 0 !== arguments[3]) || arguments[3];
          super(e, t, r), this.auto = n, this.abortHandler, this.featAggregate, this.onAggregateImported, n && (0, d.R)(e, r);
        }
        importAggregator() {
          let t = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : {};
          if (this.featAggregate || !this.auto) return;
          const r = u.il && !0 === (0, n.Mt)(this.agentIdentifier, "privacy.cookies_enabled");
          let o;
          this.onAggregateImported = new Promise(e => {
            o = e;
          });
          const a = async () => {
            let n;
            try {
              if (r) {
                const {
                  setupAgentSession: e
                } = await i.e(111).then(i.bind(i, 3228));
                n = e(this.agentIdentifier);
              }
            } catch (t) {
              (0, e.Z)("A problem occurred when starting up session manager. This page will not start or extend any session.", t);
            }
            try {
              if (!this.shouldImportAgg(this.featureName, n)) return (0, d.L)(this.agentIdentifier, this.featureName), void o(!1);
              const {
                  lazyFeatureLoader: e
                } = await i.e(111).then(i.bind(i, 8582)),
                {
                  Aggregate: r
                } = await e(this.featureName, "aggregate");
              this.featAggregate = new r(this.agentIdentifier, this.aggregator, t), o(!0);
            } catch (t) {
              (0, e.Z)("Downloading and initializing ".concat(this.featureName, " failed..."), t), this.abortHandler?.(), o(!1);
            }
          };
          u.il ? (0, f.b)(() => a(), !0) : a();
        }
        shouldImportAgg(e, t) {
          return e !== r.D.sessionReplay || !!n.Yu.MO && !1 !== (0, n.Mt)(this.agentIdentifier, "session_trace.enabled") && (!!t?.isNew || !!t?.state.sessionReplay);
        }
      }
      var p = i(7633),
        g = i(7894);
      class m extends h {
        static featureName = p.t9;
        constructor(e, t) {
          let i = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
          if (super(e, t, p.t9, i), ("undefined" == typeof PerformanceNavigationTiming || u.Tt) && "undefined" != typeof PerformanceTiming) {
            const t = (0, n.OP)(e);
            t[p.Dz] = Math.max(Date.now() - t.offset, 0), (0, f.K)(() => t[p.qw] = Math.max((0, g.z)() - t[p.Dz], 0)), (0, f.b)(() => {
              const e = (0, g.z)();
              t[p.OJ] = Math.max(e - t[p.Dz], 0), (0, c.p)("timing", ["load", e], void 0, r.D.pageViewTiming, this.ee);
            });
          }
          this.importAggregator();
        }
      }
      var v = i(1117),
        b = i(1284);
      class y extends v.w {
        constructor(e) {
          super(e), this.aggregatedData = {};
        }
        store(e, t, r, n, i) {
          var o = this.getBucket(e, t, r, i);
          return o.metrics = function (e, t) {
            t || (t = {
              count: 0
            });
            return t.count += 1, (0, b.D)(e, function (e, r) {
              t[e] = w(r, t[e]);
            }), t;
          }(n, o.metrics), o;
        }
        merge(e, t, r, n, i) {
          var o = this.getBucket(e, t, n, i);
          if (o.metrics) {
            var a = o.metrics;
            a.count += r.count, (0, b.D)(r, function (e, t) {
              if ("count" !== e) {
                var n = a[e],
                  i = r[e];
                i && !i.c ? a[e] = w(i.t, n) : a[e] = function (e, t) {
                  if (!t) return e;
                  t.c || (t = A(t.t));
                  return t.min = Math.min(e.min, t.min), t.max = Math.max(e.max, t.max), t.t += e.t, t.sos += e.sos, t.c += e.c, t;
                }(i, a[e]);
              }
            });
          } else o.metrics = r;
        }
        storeMetric(e, t, r, n) {
          var i = this.getBucket(e, t, r);
          return i.stats = w(n, i.stats), i;
        }
        getBucket(e, t, r, n) {
          this.aggregatedData[e] || (this.aggregatedData[e] = {});
          var i = this.aggregatedData[e][t];
          return i || (i = this.aggregatedData[e][t] = {
            params: r || {}
          }, n && (i.custom = n)), i;
        }
        get(e, t) {
          return t ? this.aggregatedData[e] && this.aggregatedData[e][t] : this.aggregatedData[e];
        }
        take(e) {
          for (var t = {}, r = "", n = !1, i = 0; i < e.length; i++) t[r = e[i]] = x(this.aggregatedData[r]), t[r].length && (n = !0), delete this.aggregatedData[r];
          return n ? t : null;
        }
      }
      function w(e, t) {
        return null == e ? function (e) {
          e ? e.c++ : e = {
            c: 1
          };
          return e;
        }(t) : t ? (t.c || (t = A(t.t)), t.c += 1, t.t += e, t.sos += e * e, e > t.max && (t.max = e), e < t.min && (t.min = e), t) : {
          t: e
        };
      }
      function A(e) {
        return {
          t: e,
          min: e,
          max: e,
          sos: e * e,
          c: 1
        };
      }
      function x(e) {
        return "object" != typeof e ? [] : (0, b.D)(e, E);
      }
      function E(e, t) {
        return t;
      }
      var T = i(8632),
        _ = i(4402),
        D = i(4351);
      var j = i(7956),
        C = i(3239),
        N = i(9251);
      class O extends h {
        static featureName = N.t;
        constructor(e, t) {
          let r = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
          super(e, t, N.t, r), u.il && ((0, n.OP)(e).initHidden = Boolean("hidden" === document.visibilityState), (0, j.N)(() => (0, c.p)("docHidden", [(0, g.z)()], void 0, N.t, this.ee), !0), (0, C.bP)("pagehide", () => (0, c.p)("winPagehide", [(0, g.z)()], void 0, N.t, this.ee)), this.importAggregator());
        }
      }
      var S = i(3081);
      class P extends h {
        static featureName = S.t9;
        constructor(e, t) {
          let r = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
          super(e, t, S.t9, r), this.importAggregator();
        }
      }
      var R = i(6660);
      class I {
        constructor(e, t, r, n) {
          this.name = "UncaughtError", this.message = e, this.sourceURL = t, this.line = r, this.column = n;
        }
      }
      class k extends h {
        static featureName = R.t;
        #e = new Set();
        constructor(e, t) {
          let n = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
          super(e, t, R.t, n);
          try {
            this.removeOnAbort = new AbortController();
          } catch (e) {}
          this.ee.on("fn-err", (e, t, n) => {
            this.abortHandler && !this.#e.has(n) && (this.#e.add(n), (0, c.p)("err", [this.#t(n), (0, g.z)()], void 0, r.D.jserrors, this.ee));
          }), this.ee.on("internal-error", e => {
            this.abortHandler && (0, c.p)("ierr", [this.#t(e), (0, g.z)(), !0], void 0, r.D.jserrors, this.ee);
          }), u._A.addEventListener("unhandledrejection", e => {
            this.abortHandler && (0, c.p)("err", [this.#r(e), (0, g.z)(), !1, {
              unhandledPromiseRejection: 1
            }], void 0, r.D.jserrors, this.ee);
          }, (0, C.m$)(!1, this.removeOnAbort?.signal)), u._A.addEventListener("error", e => {
            this.abortHandler && (this.#e.has(e.error) ? this.#e.delete(e.error) : (0, c.p)("err", [this.#n(e), (0, g.z)()], void 0, r.D.jserrors, this.ee));
          }, (0, C.m$)(!1, this.removeOnAbort?.signal)), this.abortHandler = this.#i, this.importAggregator();
        }
        #i() {
          this.removeOnAbort?.abort(), this.#e.clear(), this.abortHandler = void 0;
        }
        #t(e) {
          return e instanceof Error ? e : void 0 !== e?.message ? new I(e.message, e.filename || e.sourceURL, e.lineno || e.line, e.colno || e.col) : new I("string" == typeof e ? e : (0, D.P)(e));
        }
        #r(e) {
          let t = "Unhandled Promise Rejection: ";
          if (e?.reason instanceof Error) try {
            return e.reason.message = t + e.reason.message, e.reason;
          } catch (t) {
            return e.reason;
          }
          if (void 0 === e.reason) return new I(t);
          const r = this.#t(e.reason);
          return r.message = t + r.message, r;
        }
        #n(e) {
          return e.error instanceof Error ? e.error : new I(e.message, e.filename, e.lineno, e.colno);
        }
      }
      var H = i(2210);
      let z = 1;
      const L = "nr@id";
      function M(e) {
        const t = typeof e;
        return !e || "object" !== t && "function" !== t ? -1 : e === u._A ? 0 : (0, H.X)(e, L, function () {
          return z++;
        });
      }
      function B(e) {
        if ("string" == typeof e && e.length) return e.length;
        if ("object" == typeof e) {
          if ("undefined" != typeof ArrayBuffer && e instanceof ArrayBuffer && e.byteLength) return e.byteLength;
          if ("undefined" != typeof Blob && e instanceof Blob && e.size) return e.size;
          if (!("undefined" != typeof FormData && e instanceof FormData)) try {
            return (0, D.P)(e).length;
          } catch (e) {
            return;
          }
        }
      }
      var F = i(1214),
        U = i(7243);
      class q {
        constructor(e) {
          this.agentIdentifier = e;
        }
        generateTracePayload(e) {
          if (!this.shouldGenerateTrace(e)) return null;
          var t = (0, n.DL)(this.agentIdentifier);
          if (!t) return null;
          var r = (t.accountID || "").toString() || null,
            i = (t.agentID || "").toString() || null,
            o = (t.trustKey || "").toString() || null;
          if (!r || !i) return null;
          var a = (0, _.M)(),
            s = (0, _.Ht)(),
            c = Date.now(),
            u = {
              spanId: a,
              traceId: s,
              timestamp: c
            };
          return (e.sameOrigin || this.isAllowedOrigin(e) && this.useTraceContextHeadersForCors()) && (u.traceContextParentHeader = this.generateTraceContextParentHeader(a, s), u.traceContextStateHeader = this.generateTraceContextStateHeader(a, c, r, i, o)), (e.sameOrigin && !this.excludeNewrelicHeader() || !e.sameOrigin && this.isAllowedOrigin(e) && this.useNewrelicHeaderForCors()) && (u.newrelicHeader = this.generateTraceHeader(a, s, c, r, i, o)), u;
        }
        generateTraceContextParentHeader(e, t) {
          return "00-" + t + "-" + e + "-01";
        }
        generateTraceContextStateHeader(e, t, r, n, i) {
          return i + "@nr=0-1-" + r + "-" + n + "-" + e + "----" + t;
        }
        generateTraceHeader(e, t, r, n, i, o) {
          if (!("function" == typeof u._A?.btoa)) return null;
          var a = {
            v: [0, 1],
            d: {
              ty: "Browser",
              ac: n,
              ap: i,
              id: e,
              tr: t,
              ti: r
            }
          };
          return o && n !== o && (a.d.tk = o), btoa((0, D.P)(a));
        }
        shouldGenerateTrace(e) {
          return this.isDtEnabled() && this.isAllowedOrigin(e);
        }
        isAllowedOrigin(e) {
          var t = !1,
            r = {};
          if ((0, n.Mt)(this.agentIdentifier, "distributed_tracing") && (r = (0, n.P_)(this.agentIdentifier).distributed_tracing), e.sameOrigin) t = !0;else if (r.allowed_origins instanceof Array) for (var i = 0; i < r.allowed_origins.length; i++) {
            var o = (0, U.e)(r.allowed_origins[i]);
            if (e.hostname === o.hostname && e.protocol === o.protocol && e.port === o.port) {
              t = !0;
              break;
            }
          }
          return t;
        }
        isDtEnabled() {
          var e = (0, n.Mt)(this.agentIdentifier, "distributed_tracing");
          return !!e && !!e.enabled;
        }
        excludeNewrelicHeader() {
          var e = (0, n.Mt)(this.agentIdentifier, "distributed_tracing");
          return !!e && !!e.exclude_newrelic_header;
        }
        useNewrelicHeaderForCors() {
          var e = (0, n.Mt)(this.agentIdentifier, "distributed_tracing");
          return !!e && !1 !== e.cors_use_newrelic_header;
        }
        useTraceContextHeadersForCors() {
          var e = (0, n.Mt)(this.agentIdentifier, "distributed_tracing");
          return !!e && !!e.cors_use_tracecontext_headers;
        }
      }
      var Z = i(7825),
        V = ["load", "error", "abort", "timeout"],
        G = V.length,
        W = n.Yu.REQ,
        X = n.Yu.XHR;
      class Q extends h {
        static featureName = Z.t;
        constructor(e, t) {
          let i = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
          super(e, t, Z.t, i), (0, n.OP)(e).xhrWrappable && (this.dt = new q(e), this.handler = (e, t, r, n) => (0, c.p)(e, t, r, n, this.ee), (0, F.u5)(this.ee), (0, F.Kf)(this.ee), function (e, t, i, o) {
            function a(e) {
              var t = this;
              t.totalCbs = 0, t.called = 0, t.cbTime = 0, t.end = E, t.ended = !1, t.xhrGuids = {}, t.lastSize = null, t.loadCaptureCalled = !1, t.params = this.params || {}, t.metrics = this.metrics || {}, e.addEventListener("load", function (r) {
                _(t, e);
              }, (0, C.m$)(!1)), u.IF || e.addEventListener("progress", function (e) {
                t.lastSize = e.loaded;
              }, (0, C.m$)(!1));
            }
            function s(e) {
              this.params = {
                method: e[0]
              }, T(this, e[1]), this.metrics = {};
            }
            function c(t, r) {
              var i = (0, n.DL)(e);
              i.xpid && this.sameOrigin && r.setRequestHeader("X-NewRelic-ID", i.xpid);
              var a = o.generateTracePayload(this.parsedOrigin);
              if (a) {
                var s = !1;
                a.newrelicHeader && (r.setRequestHeader("newrelic", a.newrelicHeader), s = !0), a.traceContextParentHeader && (r.setRequestHeader("traceparent", a.traceContextParentHeader), a.traceContextStateHeader && r.setRequestHeader("tracestate", a.traceContextStateHeader), s = !0), s && (this.dt = a);
              }
            }
            function d(e, r) {
              var n = this.metrics,
                i = e[0],
                o = this;
              if (n && i) {
                var a = B(i);
                a && (n.txSize = a);
              }
              this.startTime = (0, g.z)(), this.listener = function (e) {
                try {
                  "abort" !== e.type || o.loadCaptureCalled || (o.params.aborted = !0), ("load" !== e.type || o.called === o.totalCbs && (o.onloadCalled || "function" != typeof r.onload) && "function" == typeof o.end) && o.end(r);
                } catch (e) {
                  try {
                    t.emit("internal-error", [e]);
                  } catch (e) {}
                }
              };
              for (var s = 0; s < G; s++) r.addEventListener(V[s], this.listener, (0, C.m$)(!1));
            }
            function l(e, t, r) {
              this.cbTime += e, t ? this.onloadCalled = !0 : this.called += 1, this.called !== this.totalCbs || !this.onloadCalled && "function" == typeof r.onload || "function" != typeof this.end || this.end(r);
            }
            function f(e, t) {
              var r = "" + M(e) + !!t;
              this.xhrGuids && !this.xhrGuids[r] && (this.xhrGuids[r] = !0, this.totalCbs += 1);
            }
            function h(e, t) {
              var r = "" + M(e) + !!t;
              this.xhrGuids && this.xhrGuids[r] && (delete this.xhrGuids[r], this.totalCbs -= 1);
            }
            function p() {
              this.endTime = (0, g.z)();
            }
            function m(e, r) {
              r instanceof X && "load" === e[0] && t.emit("xhr-load-added", [e[1], e[2]], r);
            }
            function v(e, r) {
              r instanceof X && "load" === e[0] && t.emit("xhr-load-removed", [e[1], e[2]], r);
            }
            function b(e, t, r) {
              t instanceof X && ("onload" === r && (this.onload = !0), ("load" === (e[0] && e[0].type) || this.onload) && (this.xhrCbStart = (0, g.z)()));
            }
            function y(e, r) {
              this.xhrCbStart && t.emit("xhr-cb-time", [(0, g.z)() - this.xhrCbStart, this.onload, r], r);
            }
            function w(e) {
              var t,
                r = e[1] || {};
              if ("string" == typeof e[0] ? 0 === (t = e[0]).length && u.il && (t = "" + u._A.location.href) : e[0] && e[0].url ? t = e[0].url : u._A?.URL && e[0] && e[0] instanceof URL ? t = e[0].href : "function" == typeof e[0].toString && (t = e[0].toString()), "string" == typeof t && 0 !== t.length) {
                t && (this.parsedOrigin = (0, U.e)(t), this.sameOrigin = this.parsedOrigin.sameOrigin);
                var n = o.generateTracePayload(this.parsedOrigin);
                if (n && (n.newrelicHeader || n.traceContextParentHeader)) if (e[0] && e[0].headers) s(e[0].headers, n) && (this.dt = n);else {
                  var i = {};
                  for (var a in r) i[a] = r[a];
                  i.headers = new Headers(r.headers || {}), s(i.headers, n) && (this.dt = n), e.length > 1 ? e[1] = i : e.push(i);
                }
              }
              function s(e, t) {
                var r = !1;
                return t.newrelicHeader && (e.set("newrelic", t.newrelicHeader), r = !0), t.traceContextParentHeader && (e.set("traceparent", t.traceContextParentHeader), t.traceContextStateHeader && e.set("tracestate", t.traceContextStateHeader), r = !0), r;
              }
            }
            function A(e, t) {
              this.params = {}, this.metrics = {}, this.startTime = (0, g.z)(), this.dt = t, e.length >= 1 && (this.target = e[0]), e.length >= 2 && (this.opts = e[1]);
              var r,
                n = this.opts || {},
                i = this.target;
              "string" == typeof i ? r = i : "object" == typeof i && i instanceof W ? r = i.url : u._A?.URL && "object" == typeof i && i instanceof URL && (r = i.href), T(this, r);
              var o = ("" + (i && i instanceof W && i.method || n.method || "GET")).toUpperCase();
              this.params.method = o, this.txSize = B(n.body) || 0;
            }
            function x(e, t) {
              var n;
              this.endTime = (0, g.z)(), this.params || (this.params = {}), this.params.status = t ? t.status : 0, "string" == typeof this.rxSize && this.rxSize.length > 0 && (n = +this.rxSize);
              var o = {
                txSize: this.txSize,
                rxSize: n,
                duration: (0, g.z)() - this.startTime
              };
              i("xhr", [this.params, o, this.startTime, this.endTime, "fetch"], this, r.D.ajax);
            }
            function E(e) {
              var t = this.params,
                n = this.metrics;
              if (!this.ended) {
                this.ended = !0;
                for (var o = 0; o < G; o++) e.removeEventListener(V[o], this.listener, !1);
                t.aborted || (n.duration = (0, g.z)() - this.startTime, this.loadCaptureCalled || 4 !== e.readyState ? null == t.status && (t.status = 0) : _(this, e), n.cbTime = this.cbTime, i("xhr", [t, n, this.startTime, this.endTime, "xhr"], this, r.D.ajax));
              }
            }
            function T(e, t) {
              var r = (0, U.e)(t),
                n = e.params;
              n.hostname = r.hostname, n.port = r.port, n.protocol = r.protocol, n.host = r.hostname + ":" + r.port, n.pathname = r.pathname, e.parsedOrigin = r, e.sameOrigin = r.sameOrigin;
            }
            function _(e, t) {
              e.params.status = t.status;
              var r = function (e, t) {
                var r = e.responseType;
                return "json" === r && null !== t ? t : "arraybuffer" === r || "blob" === r || "json" === r ? B(e.response) : "text" === r || "" === r || void 0 === r ? B(e.responseText) : void 0;
              }(t, e.lastSize);
              if (r && (e.metrics.rxSize = r), e.sameOrigin) {
                var n = t.getResponseHeader("X-NewRelic-App-Data");
                n && (e.params.cat = n.split(", ").pop());
              }
              e.loadCaptureCalled = !0;
            }
            t.on("new-xhr", a), t.on("open-xhr-start", s), t.on("open-xhr-end", c), t.on("send-xhr-start", d), t.on("xhr-cb-time", l), t.on("xhr-load-added", f), t.on("xhr-load-removed", h), t.on("xhr-resolved", p), t.on("addEventListener-end", m), t.on("removeEventListener-end", v), t.on("fn-end", y), t.on("fetch-before-start", w), t.on("fetch-start", A), t.on("fn-start", b), t.on("fetch-done", x);
          }(e, this.ee, this.handler, this.dt), this.importAggregator());
        }
      }
      var K = i(3614);
      const {
        BST_RESOURCE: Y,
        RESOURCE: J,
        START: ee,
        END: te,
        FEATURE_NAME: re,
        FN_END: ne,
        FN_START: ie,
        PUSH_STATE: oe
      } = K;
      var ae = i(7836);
      const {
        FEATURE_NAME: se,
        START: ce,
        END: ue,
        BODY: de,
        CB_END: le,
        JS_TIME: fe,
        FETCH: he,
        FN_START: pe,
        CB_START: ge,
        FN_END: me
      } = ae;
      var ve = i(4649);
      class be extends h {
        static featureName = ve.t;
        constructor(e, t) {
          let r = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2];
          super(e, t, ve.t, r), this.importAggregator();
        }
      }
      new class extends t {
        constructor(t) {
          let r = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : (0, _.ky)(16);
          super(), u._A ? (this.agentIdentifier = r, this.sharedAggregator = new y({
            agentIdentifier: this.agentIdentifier
          }), this.features = {}, this.desiredFeatures = new Set(t.features || []), this.desiredFeatures.add(m), Object.assign(this, (0, s.j)(this.agentIdentifier, t, t.loaderType || "agent")), this.start()) : (0, e.Z)("Failed to initial the agent. Could not determine the runtime environment.");
        }
        get config() {
          return {
            info: (0, n.C5)(this.agentIdentifier),
            init: (0, n.P_)(this.agentIdentifier),
            loader_config: (0, n.DL)(this.agentIdentifier),
            runtime: (0, n.OP)(this.agentIdentifier)
          };
        }
        start() {
          const t = "features";
          try {
            const n = a(this.agentIdentifier),
              i = [...this.desiredFeatures];
            i.sort((e, t) => r.p[e.featureName] - r.p[t.featureName]), i.forEach(t => {
              if (n[t.featureName] || t.featureName === r.D.pageViewEvent) {
                const i = function (e) {
                  switch (e) {
                    case r.D.ajax:
                      return [r.D.jserrors];
                    case r.D.sessionTrace:
                      return [r.D.ajax, r.D.pageViewEvent];
                    case r.D.sessionReplay:
                      return [r.D.sessionTrace];
                    case r.D.pageViewTiming:
                      return [r.D.pageViewEvent];
                    default:
                      return [];
                  }
                }(t.featureName);
                i.every(e => n[e]) || (0, e.Z)("".concat(t.featureName, " is enabled but one or more dependent features has been disabled (").concat((0, D.P)(i), "). This may cause unintended consequences or missing data...")), this.features[t.featureName] = new t(this.agentIdentifier, this.sharedAggregator);
              }
            }), (0, T.Qy)(this.agentIdentifier, this.features, t);
          } catch (r) {
            (0, e.Z)("Failed to initialize all enabled instrument classes (agent aborted) -", r);
            for (const e in this.features) this.features[e].abortHandler?.();
            const n = (0, T.fP)();
            return delete n.initializedAgents[this.agentIdentifier]?.api, delete n.initializedAgents[this.agentIdentifier]?.[t], delete this.sharedAggregator, n.ee?.abort(), delete n.ee?.get(this.agentIdentifier), !1;
          }
        }
        addToTrace(t) {
          (0, e.Z)("Call to agent api addToTrace failed. The page action feature is not currently initialized.");
        }
        setCurrentRouteName(t) {
          (0, e.Z)("Call to agent api setCurrentRouteName failed. The spa feature is not currently initialized.");
        }
        interaction() {
          (0, e.Z)("Call to agent api interaction failed. The spa feature is not currently initialized.");
        }
      }({
        features: [Q, m, O, class extends h {
          static featureName = re;
          constructor(e, t) {
            if (super(e, t, re, !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2]), !u.il) return;
            const n = this.ee;
            let i;
            (0, F.QU)(n), this.eventsEE = (0, F.em)(n), this.eventsEE.on(ie, function (e, t) {
              this.bstStart = (0, g.z)();
            }), this.eventsEE.on(ne, function (e, t) {
              (0, c.p)("bst", [e[0], t, this.bstStart, (0, g.z)()], void 0, r.D.sessionTrace, n);
            }), n.on(oe + ee, function (e) {
              this.time = (0, g.z)(), this.startPath = location.pathname + location.hash;
            }), n.on(oe + te, function (e) {
              (0, c.p)("bstHist", [location.pathname + location.hash, this.startPath, this.time], void 0, r.D.sessionTrace, n);
            });
            try {
              i = new PerformanceObserver(e => {
                const t = e.getEntries();
                (0, c.p)(Y, [t], void 0, r.D.sessionTrace, n);
              }), i.observe({
                type: J,
                buffered: !0
              });
            } catch (e) {}
            this.importAggregator({
              resourceObserver: i
            });
          }
        }, P, be, k, class extends h {
          static featureName = se;
          constructor(e, t) {
            if (super(e, t, se, !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2]), !u.il) return;
            if (!(0, n.OP)(e).xhrWrappable) return;
            try {
              this.removeOnAbort = new AbortController();
            } catch (e) {}
            let r,
              i = 0;
            const o = this.ee.get("tracer"),
              a = (0, F._L)(this.ee),
              s = (0, F.Lg)(this.ee),
              c = (0, F.BV)(this.ee),
              d = (0, F.Kf)(this.ee),
              l = this.ee.get("events"),
              f = (0, F.u5)(this.ee),
              h = (0, F.QU)(this.ee),
              p = (0, F.Gm)(this.ee);
            function m(e, t) {
              h.emit("newURL", ["" + window.location, t]);
            }
            function v() {
              i++, r = window.location.hash, this[pe] = (0, g.z)();
            }
            function b() {
              i--, window.location.hash !== r && m(0, !0);
              var e = (0, g.z)();
              this[fe] = ~~this[fe] + e - this[pe], this[me] = e;
            }
            function y(e, t) {
              e.on(t, function () {
                this[t] = (0, g.z)();
              });
            }
            this.ee.on(pe, v), s.on(ge, v), a.on(ge, v), this.ee.on(me, b), s.on(le, b), a.on(le, b), this.ee.buffer([pe, me, "xhr-resolved"], this.featureName), l.buffer([pe], this.featureName), c.buffer(["setTimeout" + ue, "clearTimeout" + ce, pe], this.featureName), d.buffer([pe, "new-xhr", "send-xhr" + ce], this.featureName), f.buffer([he + ce, he + "-done", he + de + ce, he + de + ue], this.featureName), h.buffer(["newURL"], this.featureName), p.buffer([pe], this.featureName), s.buffer(["propagate", ge, le, "executor-err", "resolve" + ce], this.featureName), o.buffer([pe, "no-" + pe], this.featureName), a.buffer(["new-jsonp", "cb-start", "jsonp-error", "jsonp-end"], this.featureName), y(f, he + ce), y(f, he + "-done"), y(a, "new-jsonp"), y(a, "jsonp-end"), y(a, "cb-start"), h.on("pushState-end", m), h.on("replaceState-end", m), window.addEventListener("hashchange", m, (0, C.m$)(!0, this.removeOnAbort?.signal)), window.addEventListener("load", m, (0, C.m$)(!0, this.removeOnAbort?.signal)), window.addEventListener("popstate", function () {
              m(0, i > 1);
            }, (0, C.m$)(!0, this.removeOnAbort?.signal)), this.abortHandler = this.#i, this.importAggregator();
          }
          #i() {
            this.removeOnAbort?.abort(), this.abortHandler = void 0;
          }
        }],
        loaderType: "spa"
      });
    })();
  })();
})()</script>
      <link rel='shortcut icon' href='https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/103/images/favSD.ico' type='image/x-icon' />
      <link rel='icon' href='https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/103/images/favSD.ico' type='image/x-icon'>
      <link rel='stylesheet' href='https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1/arp.css'>
      <link href="//cdn.pendo.io" rel="dns-prefetch" />
      <link href="https://cdn.pendo.io" rel="preconnect" crossorigin="anonymous" />
      <link rel='dns-prefetch' href='https://smetrics.elsevier.com'>
      
      <script type="48d55d7d34a7ef35ff792557-text/javascript">
        var targetServerState = JSON.stringify({"4D6368F454EC41940A4C98A6@AdobeOrg":{"sdid":{"supplementalDataIDCurrent":"619656D012CC3294-43F6558FF5791D0E","supplementalDataIDCurrentConsumed":{"payload:target-global-mbox":true},"supplementalDataIDLastConsumed":{}}}});
        window.appData = window.appData || [];
        window.pageTargeting = {"region":"eu-west-1","platform":"sdtech","entitled":false,"crawler":"","journal":"Medical Image Analysis","auth":"AE"};
        window.arp = {
          config: {"adobeSuite":"elsevier-sd-prod","arsUrl":"https://ars.els-cdn.com","assetRoute":"https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1","recommendationsFeedback":{"enabled":true,"url":"https://feedback.recs.d.elsevier.com/raw/events","timeout":60000},"googleMapsApiKey":"AIzaSyCBYU6I6lrbEU6wQXUEIte3NwGtm3jwHQc","mediaBaseUrl":"https://ars.els-cdn.com/content/image/","strictMode":false,"seamlessAccess":{"enableSeamlessAccess":true,"scriptUrl":"https://unpkg.com/@theidentityselector/thiss-ds@1.0.13/dist/thiss-ds.js","persistenceUrl":"https://service.seamlessaccess.org/ps/","persistenceContext":"seamlessaccess.org","scienceDirectUrl":"https://www.sciencedirect.com","shibAuthUrl":"https://auth.elsevier.com/ShibAuth/institutionLogin"},"reaxys":{"apiUrl":"https://reaxys-sdlc.reaxys.com","origin":"sciencedirect","queryBuilderHostPath":"https://www.reaxys.com/reaxys/secured/hopinto.do","url":"https://www.reaxys.com"},"oneTrustCookie":{"enabled":true},"ssrn":{"url":"https://papers.ssrn.com","path":"/sol3/papers.cfm"}},
          subscriptions: [],
          subscribe: function(cb) {
            var self = this;
            var i = this.subscriptions.push(cb) - 1;
            return function unsubscribe() {
              self.subscriptions.splice(i, 1);
            }
          },
        };
        window.addEventListener('beforeprint', () => pendo.onGuideDismissed());
      </script>
    </head>
    <body data-sd-ui-layer-boundary="true">
      <script type="48d55d7d34a7ef35ff792557-text/javascript">
        window.__PRELOADED_STATE__ = {"abstracts":{"content":[{"$$":[{"$":{"id":"d1e9157"},"#name":"section-title","_":"Abstract"},{"$$":[{"$$":[{"#name":"__text__","_":"Resting-state functional magnetic resonance imaging (rs-fMRI) provides a non-invasive imaging technique to study patterns of brain activity, and is increasingly used to facilitate automated brain disorder analysis. Existing fMRI-based learning methods often rely on labeled data to construct learning models, while the data annotation process typically requires significant time and resource investment. Graph contrastive learning offers a promising solution to address the small labeled data issue, by augmenting fMRI time series for self-supervised learning. However, data augmentation strategies employed in these approaches may damage the original blood-oxygen-level-dependent (BOLD) signals, thus hindering subsequent fMRI feature extraction. In this paper, we propose a self-supervised graph contrastive learning framework with diffusion augmentation (GCDA) for functional MRI analysis. The GCDA consists of a "},{"#name":"italic","_":"pretext model"},{"#name":"__text__","_":" and a "},{"#name":"italic","_":"task-specific model"},{"#name":"__text__","_":". In the pretext model, we first augment each brain functional connectivity network derived from fMRI through a graph diffusion augmentation (GDA) module, and then use two graph isomorphism networks with shared parameters to extract features in a self-supervised contrastive learning manner. The pretext model can be optimized without the need for labeled training data, while the GDA focuses on perturbing graph edges and nodes, thus preserving the integrity of original BOLD signals. The task-specific model involves fine-tuning the trained pretext model to adapt to downstream tasks. Experimental results on two rs-fMRI cohorts with a total of 1230 subjects demonstrate the effectiveness of our method compared with several state-of-the-arts."}],"$":{"view":"all","id":"d1e9160"},"#name":"simple-para"}],"$":{"view":"all","id":"d1e9159"},"#name":"abstract-sec"}],"$":{"view":"all","id":"d1e9156","class":"author"},"#name":"abstract"},{"$$":[{"$":{"id":"d1e9169"},"#name":"section-title","_":"Graphical abstract"},{"$$":[{"$$":[{"$$":[{"$$":[{"$":{"role":"http://data.elsevier.com/vocabulary/ElsevierContentTypes/23.4","xmlns:xlink":true,"id":"d1e9176","href":"pii:S1361841524003281/ga1","locator":"ga1"},"#name":"link"}],"$":{"id":"dfig1"},"#name":"figure"}],"#name":"display"}],"$":{"view":"all","id":"d1e9172"},"#name":"simple-para"}],"$":{"view":"all","id":"d1e9171"},"#name":"abstract-sec"}],"$":{"view":"all","id":"d1e9168","class":"graphical"},"#name":"abstract"},{"$$":[{"$":{"id":"d1e9178"},"#name":"section-title","_":"Highlights"},{"$$":[{"$$":[{"$$":[{"$$":[{"#name":"label","_":"•"},{"$":{"view":"all","id":"d1e9187"},"#name":"para","_":"Creating a self-supervised graph contrastive learning framework for fMRI analysis and brain disease detection to alleviate the small-sample-size problem."}],"$":{"id":"d1e9184"},"#name":"list-item"},{"$$":[{"#name":"label","_":"•"},{"$":{"view":"all","id":"d1e9192"},"#name":"para","_":"Designing a graph diffusion augmentation strategy to preserve the integrity of original BOLD signals."}],"$":{"id":"d1e9189"},"#name":"list-item"},{"$$":[{"#name":"label","_":"•"},{"$":{"view":"all","id":"d1e9197"},"#name":"para","_":"Conducting extensive experiments on two rs-fMRI datasets with 1,230 subjects."}],"$":{"id":"d1e9194"},"#name":"list-item"}],"$":{"id":"d1e9183"},"#name":"list"}],"$":{"view":"all","id":"d1e9181"},"#name":"simple-para"}],"$":{"view":"all","id":"d1e9180"},"#name":"abstract-sec"}],"$":{"view":"all","id":"d1e9177","class":"author-highlights"},"#name":"abstract"}],"floats":[],"footnotes":[],"attachments":[{"attachment-eid":"1-s2.0-S1361841524003281-ga1.jpg","ucs-locator":"https://s3-eu-west-1.amazonaws.com/prod-ucs-content-store-eu-west/content/pii:S1361841524003281/ga1/DOWNSAMPLED/image/jpeg/281dab2504aae219ce08c1519c6db389/ga1.jpg","file-basename":"ga1","abstract-attachment":"true","filename":"ga1.jpg","extension":"jpg","filesize":"94434","pixel-height":"143","pixel-width":"301","attachment-type":"IMAGE-DOWNSAMPLED"},{"attachment-eid":"1-s2.0-S1361841524003281-ga1.sml","ucs-locator":"https://s3-eu-west-1.amazonaws.com/prod-ucs-content-store-eu-west/content/pii:S1361841524003281/ga1/THUMBNAIL/image/gif/c2603936af32920818c85102a3cd34eb/ga1.sml","file-basename":"ga1","abstract-attachment":"true","filename":"ga1.sml","extension":"sml","filesize":"79938","pixel-height":"104","pixel-width":"219","attachment-type":"IMAGE-THUMBNAIL"},{"attachment-eid":"1-s2.0-S1361841524003281-ga1_lrg.jpg","ucs-locator":"https://s3-eu-west-1.amazonaws.com/prod-ucs-content-store-eu-west/content/pii:S1361841524003281/HIGHRES/image/jpeg/964a4ff1fbb892106c952ed9fa1da7f7/ga1_lrg.jpg","file-basename":"ga1","abstract-attachment":"true","filename":"ga1_lrg.jpg","extension":"jpg","filesize":"289932","pixel-height":"633","pixel-width":"1333","attachment-type":"IMAGE-HIGH-RES"}]},"accessbarConfig":{"fallback":false,"id":"accessbar","version":"0.0.1","analytics":{"location":"accessbar","eventName":"ctaImpression"},"ariaLabel":{"accessbar":"Download options and search","componentsList":"PDF Options"},"banners":[{"id":"BannerSsrn"}],"components":[{"analytics":[{"ids":["accessbar:clinicalkeycta:inst-known:sdcust-unknown:ent-no:ra-no:source-linkinghub:method-ip"],"eventName":"ctaClick"}],"label":"Access through&nbsp;**ClinicalKey**","id":"ClinicalKey"},{"ariaLabel":"Access through your organization","institutionLogoAltText":"Seamless access","analytics":[{"ids":["accessbar:accesscta:inst-unknown:sdcust-unknown:ent-unknown:ra-yes:source-seamlessaccess:method-shib"],"eventName":"ctaClick"}],"labelPrefix":"Access through","defaultLabelSuffix":"your organization","href":"/user/institution/login?targetUrl=%2Fscience%2Farticle%2Fpii%2FS1361841524003281","id":"RemoteAccess"},{"analytics":[{"ids":["accessbar:purchase-pdf"],"eventName":"ctaClick"}],"label":"Purchase PDF","href":"/getaccess/pii/S1361841524003281/purchase","rel":"noreferrer noopener","target":"_blank","id":"PurchasePDF"},{"analytics":[{"ids":["accessbar:patient-access"],"eventName":"ctaClick"}],"label":"Patient Access","href":"https://www.elsevier.com/open-science/science-and-society/access-for-healthcare-and-patients","rel":"noreferrer noopener","target":"_blank","id":"PatientAccess"},{"analytics":[{"ids":["accessbar:another-institution"],"eventName":"ctaClick"}],"label":"Access through another organization","href":"/user/institution/login?targetUrl=%2Fscience%2Farticle%2Fpii%2FS1361841524003281","id":"RemoteAccessOther"},{"id":"ViewClinicalKeyFullText","analytics":[{"eventName":"ctaClick","ids":["accessbar:fta:clinical-key"]}],"label":"View full text","rel":"noopener noreferrer","target":"_blank","href":"https://www.clinicalkey.com/#!/content/journal/1-s2.0-S1361841524003281"}],"search":{"inputPlaceHolder":"Search ScienceDirect","ariaLabel":{"input":"Search ScienceDirect","submit":"Submit search"},"formAction":"/search#submit","analytics":[{"ids":["accessbar:search"],"eventName":"searchStart"}],"id":"QuickSearch"}},"adobeTarget":{"sd:genai-question-and-answer":{}},"article":{"accessOptions":{},"analyticsMetadata":{"accountId":"228598","accountName":"ScienceDirect Guests","loginStatus":"anonymous","userId":"12975512","isLoggedIn":false},"article-number":"103403","cid":"272154","content-family":"serial","copyright-line":"© 2024 Elsevier B.V. All rights are reserved, including those for text and data mining, AI training, and similar technologies.","cover-date-years":["2025"],"cover-date-start":"2025-04-01","cover-date-text":"April 2025","document-subtype":"fla","document-type":"article","eid":"1-s2.0-S1361841524003281","doi":"10.1016/j.media.2024.103403","first-fp":"103403","hub-eid":"1-s2.0-S1361841524X00092","issuePii":"S1361841524X00092","item-weight":"FULL-TEXT","language":"en","last-author":{"#name":"last-author","$":{"xmlns:ce":true,"xmlns:dm":true,"xmlns:sb":true},"$$":[{"#name":"author","$":{"author-id":"S1361841524003281-db3283f763039ca85f730090ba02ee57","id":"au000006","orcid":"0000-0002-0166-0807"},"$$":[{"#name":"given-name","_":"Mingxia"},{"#name":"surname","_":"Liu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e9103","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e9106","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"encoded-e-address","__encoded":"JTdCJTIyJTIzbmFtZSUyMiUzQSUyMmUtYWRkcmVzcyUyMiUyQyUyMiUyNCUyMiUzQSU3QiUyMnhtbG5zJTNBeGxpbmslMjIlM0F0cnVlJTJDJTIyaWQlMjIlM0ElMjJlYTElMjIlMkMlMjJ0eXBlJTIyJTNBJTIyZW1haWwlMjIlMkMlMjJocmVmJTIyJTNBJTIybWFpbHRvJTNBbWluZ3hpYV9saXUlNDBtZWQudW5jLmVkdSUyMiU3RCUyQyUyMl8lMjIlM0ElMjJtaW5neGlhX2xpdSU0MG1lZC51bmMuZWR1JTIyJTdE"}]}]},"normalized-first-auth-initial":"X","normalized-first-auth-surname":"WANG","open-research":{"#name":"open-research","$":{"xmlns:xocs":true},"$$":[{"#name":"or-agreements","$$":[{"#name":"or-agreement","$$":[{"#name":"or-agreement-name","_":"NR_NIHGRN"},{"#name":"or-agreement-terms","_":"publishAcceptedManuscriptIndexable"}]}]},{"#name":"or-agreement-license","_":"http://www.elsevier.com/open-access/userlicense/1.0/"}]},"pages":[{"first-page":"103403"}],"pii":"S1361841524003281","self-archiving":{"#name":"self-archiving","$":{"xmlns:xocs":true},"$$":[{"#name":"sa-start-date","_":"2025-12-04T00:00:00.000Z"},{"#name":"sa-user-license","_":"http://creativecommons.org/licenses/by-nc-nd/4.0/"}]},"srctitle":"Medical Image Analysis","suppl":"C","timestamp":"2025-02-03T10:21:26.188327Z","title":{"content":[{"#name":"title","$":{"id":"d1e9032"},"_":"Self-supervised graph contrastive learning with diffusion augmentation for functional MRI analysis and brain disorder detection"}],"floats":[],"footnotes":[],"attachments":[]},"vol-first":"101","vol-iss-suppl-text":"Volume 101","userSettings":{"forceAbstract":false,"creditCardPurchaseAllowed":true,"blockFullTextForAnonymousAccess":false,"disableWholeIssueDownload":false,"preventTransactionalAccess":false,"preventDocumentDelivery":true},"contentType":"JL","crossmark":false,"document-references":70,"freeHtmlGiven":false,"userProfile":{"departmentName":"ScienceDirect Guests","accessType":"GUEST","accountId":"228598","webUserId":"12975512","accountName":"ScienceDirect Guests","departmentId":"291352","userType":"NORMAL","hasMultipleOrganizations":false,"accountNumber":"C000228598"},"access":{"openAccess":false,"openArchive":false},"aipType":"none","articleEntitlement":{"entitled":false,"isCasaUser":false,"usageInfo":"(12975512,U|291352,D|228598,A|3,P|2,PL)(SDFE,CON|f15c2839630635475228c8f50e5f0ffe9ad7gxrqb,SSO|ANON_GUEST,ACCESS_TYPE)","entitledByAccount":false,"entitlementOrigin":"SD"},"crawlerInformation":{"canCrawlPDFContent":false,"isCrawler":false},"dates":{"Available online":"29 November 2024","Received":"10 June 2024","Revised":["7 November 2024"],"Accepted":"19 November 2024","Publication date":"1 April 2025","Version of Record":"4 December 2024"},"downloadFullIssue":false,"entitlementReason":"unsubscribed","features":["keywords","data-availability","references","preview"],"hasBody":true,"has-large-authors":false,"hasScholarlyAbstract":true,"headerConfig":{"contactUrl":"https://service.elsevier.com/app/contact/supporthub/sciencedirect/","userName":"","userEmail":"","orgName":"ScienceDirect Guests","webUserId":"12975512","libraryBanner":null,"shib_regUrl":"","tick_regUrl":"","recentInstitutions":[],"canActivatePersonalization":false,"hasInstitutionalAssociation":false,"hasMultiOrg":false,"userType":"GUEST","userAnonymity":"ANON_GUEST","allowCart":true,"environment":"prod","cdnAssetsHost":"https://sdfestaticassets-eu-west-1.sciencedirectassets.com"},"isCorpReq":false,"isPdfFullText":false,"issn":"13618415","issn-primary-formatted":"1361-8415","issRange":"","isThirdParty":false,"pageCount":13,"publication-content":{"noElsevierLogo":false,"imprintPublisher":{"displayName":"Elsevier","id":"47"},"isSpecialIssue":false,"isSampleIssue":false,"transactionsBlocked":false,"publicationOpenAccess":{"oaStatus":"","oaArticleCount":507,"openArchiveStatus":false,"openArchiveArticleCount":11,"openAccessStartDate":"","oaAllowsAuthorPaid":true},"issue-cover":{"attachment":[{"attachment-eid":"1-s2.0-S1361841524X00080-cov200h.gif","file-basename":"cov200h","extension":"gif","filename":"cov200h.gif","ucs-locator":["https://s3-eu-west-1.amazonaws.com/prod-ucs-content-store-eu-west/content/pii:S1361841524X00080/cover/DOWNSAMPLED200/image/gif/ebdda466ddb3a86b60c9626104674607/cov200h.gif"],"attachment-type":"IMAGE-COVER-H200","filesize":"11004","pixel-height":"200","pixel-width":"150"},{"attachment-eid":"1-s2.0-S1361841524X00080-cov150h.gif","file-basename":"cov150h","extension":"gif","filename":"cov150h.gif","ucs-locator":["https://s3-eu-west-1.amazonaws.com/prod-ucs-content-store-eu-west/content/pii:S136184152400286X/cover/DOWNSAMPLED150/image/gif/f9d6268690f4ca229277d7a4c674e2ae/cov150h.gif"],"attachment-type":"IMAGE-COVER-H150","filesize":"7110","pixel-height":"150","pixel-width":"113"}]},"smallCoverUrl":"https://ars.els-cdn.com/content/image/S13618415.gif","title":"medical-image-analysis","contentTypeCode":"JL","images":{"coverImage":"https://ars.els-cdn.com/content/image/1-s2.0-S1361841524X00080-cov150h.gif","logo":"https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1/image/elsevier-non-solus.png","logoAltText":"Elsevier"},"publicationCoverImageUrl":"https://ars.els-cdn.com/content/image/1-s2.0-S1361841524X00080-cov150h.gif"},"volRange":"101","titleString":"Self-supervised graph contrastive learning with diffusion augmentation for functional MRI analysis and brain disorder detection","ssrn":{},"renderingMode":"Preview","isAbstract":true,"isContentVisible":false,"ajaxLinks":{"referredToBy":true,"authorMetadata":true},"pdfEmbed":false,"displayViewFullText":false},"authors":{"content":[{"#name":"author-group","$":{"id":"d1e9035"},"$$":[{"#name":"author","$":{"author-id":"S1361841524003281-6e2f89dc1b971f0161e74475f156f801","id":"au000001","orcid":"0000-0002-9848-8125"},"$$":[{"#name":"given-name","_":"Xiaochuan"},{"#name":"surname","_":"Wang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e9047","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003281-72b41cdbe952b2b2ff7c33957a22049f","id":"au000002","orcid":"0000-0002-8769-496X"},"$$":[{"#name":"given-name","_":"Yuqi"},{"#name":"surname","_":"Fang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e9057","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003281-6a3d6124166723401cb2d08d87ca7385","id":"au000003"},"$$":[{"#name":"given-name","_":"Qianqian"},{"#name":"surname","_":"Wang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e9067","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003281-74d9eac4a5ca26a2ceb9a1843801f84f","id":"au000004","orcid":"0000-0003-1489-2102"},"$$":[{"#name":"given-name","_":"Pew-Thian"},{"#name":"surname","_":"Yap"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e9077","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003281-bc1dacc8d9796b2dfa195e3a935ef69e","id":"au000005"},"$$":[{"#name":"given-name","_":"Hongtu"},{"#name":"surname","_":"Zhu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e9087","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]}]},{"#name":"author","$":{"author-id":"S1361841524003281-db3283f763039ca85f730090ba02ee57","id":"au000006","orcid":"0000-0002-0166-0807"},"$$":[{"#name":"given-name","_":"Mingxia"},{"#name":"surname","_":"Liu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e9103","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e9106","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"encoded-e-address","__encoded":"JTdCJTIyJTIzbmFtZSUyMiUzQSUyMmUtYWRkcmVzcyUyMiUyQyUyMiUyNCUyMiUzQSU3QiUyMnhtbG5zJTNBeGxpbmslMjIlM0F0cnVlJTJDJTIyaWQlMjIlM0ElMjJlYTElMjIlMkMlMjJ0eXBlJTIyJTNBJTIyZW1haWwlMjIlMkMlMjJocmVmJTIyJTNBJTIybWFpbHRvJTNBbWluZ3hpYV9saXUlNDBtZWQudW5jLmVkdSUyMiU3RCUyQyUyMl8lMjIlM0ElMjJtaW5neGlhX2xpdSU0MG1lZC51bmMuZWR1JTIyJTdE"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003281-f2afd942d1bdab35c8b434fa3fb540ce","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill"},{"#name":"city","_":"Chapel Hill"},{"#name":"state","_":"NC"},{"#name":"postal-code","_":"27599"},{"#name":"country","$":{"iso3166-1-alpha-3":"USA"},"_":"USA"}]},{"#name":"source-text","$":{"id":"afs71"},"_":"Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003281-90b0da63a690af9202b0771c792c33ac","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"Department of Biostatistics and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Biostatistics and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill"},{"#name":"city","_":"Chapel Hill"},{"#name":"state","_":"NC"},{"#name":"postal-code","_":"27599"},{"#name":"country","$":{"iso3166-1-alpha-3":"USA"},"_":"USA"}]},{"#name":"source-text","$":{"id":"afs72"},"_":"Department of Biostatistics and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding author."}]}]}],"floats":[],"footnotes":[],"affiliations":{"aff1":{"#name":"affiliation","$":{"affiliation-id":"S1361841524003281-f2afd942d1bdab35c8b434fa3fb540ce","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill"},{"#name":"city","_":"Chapel Hill"},{"#name":"state","_":"NC"},{"#name":"postal-code","_":"27599"},{"#name":"country","$":{"iso3166-1-alpha-3":"USA"},"_":"USA"}]},{"#name":"source-text","$":{"id":"afs71"},"_":"Department of Radiology and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"}]},"aff2":{"#name":"affiliation","$":{"affiliation-id":"S1361841524003281-90b0da63a690af9202b0771c792c33ac","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"Department of Biostatistics and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Biostatistics and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill"},{"#name":"city","_":"Chapel Hill"},{"#name":"state","_":"NC"},{"#name":"postal-code","_":"27599"},{"#name":"country","$":{"iso3166-1-alpha-3":"USA"},"_":"USA"}]},{"#name":"source-text","$":{"id":"afs72"},"_":"Department of Biostatistics and Biomedical Research Imaging Center, University of North Carolina at Chapel Hill, Chapel Hill, NC 27599, USA"}]}},"correspondences":{"cor1":{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding author."}]}},"attachments":[],"scopusAuthorIds":{},"articles":{}},"authorMetadata":[],"banner":{"expanded":false},"biographies":{},"body":{},"chapters":{"toc":[],"isLoading":false},"changeViewLinks":{"showFullTextLink":true,"showAbstractLink":false},"citingArticles":{"hitCount":0,"viewMoreUrl":"http://www.scopus.com/scopus/inward/citedby.url?partnerID=10&rel=3.0.0&eid=2-s2.0-85210651193&md5=75a4782dd2daa961848a28d98cd4d6","articles":[]},"clientConfig":{"adobeSuite":"elsevier-sd-prod","arsUrl":"https://ars.els-cdn.com","assetRoute":"https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1","recommendationsFeedback":{"enabled":true,"url":"https://feedback.recs.d.elsevier.com/raw/events","timeout":60000},"googleMapsApiKey":"AIzaSyCBYU6I6lrbEU6wQXUEIte3NwGtm3jwHQc","mediaBaseUrl":"https://ars.els-cdn.com/content/image/","strictMode":false,"seamlessAccess":{"enableSeamlessAccess":true,"scriptUrl":"https://unpkg.com/@theidentityselector/thiss-ds@1.0.13/dist/thiss-ds.js","persistenceUrl":"https://service.seamlessaccess.org/ps/","persistenceContext":"seamlessaccess.org","scienceDirectUrl":"https://www.sciencedirect.com","shibAuthUrl":"https://auth.elsevier.com/ShibAuth/institutionLogin"},"reaxys":{"apiUrl":"https://reaxys-sdlc.reaxys.com","origin":"sciencedirect","queryBuilderHostPath":"https://www.reaxys.com/reaxys/secured/hopinto.do","url":"https://www.reaxys.com"},"oneTrustCookie":{"enabled":true},"ssrn":{"url":"https://papers.ssrn.com","path":"/sol3/papers.cfm"}},"combinedContentItems":{"content":[{"#name":"keywords","$$":[{"#name":"keywords","$":{"xmlns:ce":true,"xmlns:aep":true,"xmlns:xoe":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"class":"keyword","id":"d1e9199","view":"all","lang":"en"},"$$":[{"#name":"section-title","$":{"id":"d1e9200"},"_":"Keywords"},{"#name":"keyword","$":{"id":"d1e9202"},"$$":[{"#name":"text","_":"Functional MRI"}]},{"#name":"keyword","$":{"id":"d1e9205"},"$$":[{"#name":"text","_":"Data augmentation"}]},{"#name":"keyword","$":{"id":"d1e9208"},"$$":[{"#name":"text","_":"Diffusion model"}]},{"#name":"keyword","$":{"id":"d1e9211"},"$$":[{"#name":"text","_":"Contrastive learning"}]}]}]},{"#name":"data-availability","$":{"xmlns:ce":true,"xmlns:aep":true,"xmlns:xoe":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"da1","view":"all"},"$$":[{"#name":"section-title","$":{"id":"d1e9216"},"_":"Data availability"},{"#name":"para","$":{"id":"d1e9218","view":"all"},"_":"Data will be made available on request."}]}],"floats":[],"footnotes":[],"attachments":[]},"crossMark":{"isOpen":false},"domainConfig":{"assetRoute":"https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1","cdnAssetsHost":"https://sdfestaticassets-eu-west-1.sciencedirectassets.com"},"downloadIssue":{"openOnPageLoad":false,"isOpen":false,"downloadCapOpen":false,"articles":[],"selected":[]},"enrichedContent":{"tableOfContents":false,"researchData":{"hasResearchData":false,"dataProfile":{},"openData":{},"mendeleyData":{},"databaseLinking":{}},"geospatialData":{"attachments":[]},"interactiveCaseInsights":{},"virtualMicroscope":{}},"entitledRecommendations":{"openOnPageLoad":false,"isOpen":false,"articles":[],"selected":[],"currentPage":1,"totalPages":1},"exam":{},"helpText":{"keyDates":{"html":"<div class=\"key-dates-help\"><h3 class=\"u-margin-s-bottom u-h4\">Publication milestones</h3><p class=\"u-margin-m-bottom\">The dates displayed for an article provide information on when various publication milestones were reached at the journal that has published the article. Where applicable, activities on preceding journals at which the article was previously under consideration are not shown (for instance submission, revisions, rejection).</p><p class=\"u-margin-xs-bottom\">The publication milestones include:</p><ul class=\"key-dates-help-list u-margin-m-bottom u-padding-s-left\"><li><span class=\"u-text-italic\">Received</span>: The date the article was originally submitted to the journal.</li><li><span class=\"u-text-italic\">Revised</span>: The date the most recent revision of the article was submitted to the journal. Dates corresponding to intermediate revisions are not shown.</li><li><span class=\"u-text-italic\">Accepted</span>: The date the article was accepted for publication in the journal.</li><li><span class=\"u-text-italic\">Available online</span>: The date a version of the article was made available online in the journal.</li><li><span class=\"u-text-italic\">Version of Record</span>: The date the finalized version of the article was made available in the journal.</li></ul><p>More information on publishing policies can be found on the <a class=\"anchor anchor-secondary u-display-inline anchor-underline\" href=\"https://www.elsevier.com/about/policies-and-standards/publishing-ethics\" target=\"_blank\"><span class=\"anchor-text-container\"><span class=\"anchor-text\">Publishing Ethics Policies</span></span></a> page. View our <a class=\"anchor anchor-secondary u-display-inline anchor-underline\" href=\"https://www.elsevier.com/researcher/author/submit-your-paper\" target=\"_blank\"><span class=\"anchor-text-container\"><span class=\"anchor-text\">Publishing with Elsevier: step-by-step</span></span></a> page to learn more about the publishing process. For any questions on your own submission or other questions related to publishing an article, <a class=\"anchor anchor-secondary u-display-inline anchor-underline\" href=\"https://service.elsevier.com/app/phone/supporthub/publishing\" target=\"_blank\"><span class=\"anchor-text-container\"><span class=\"anchor-text\">contact our Researcher support team.</span></span></a></p></div>","title":"What do these dates mean?"}},"glossary":{},"issueNavigation":{"previous":{},"next":{}},"linkingHubLinks":{},"metrics":{"metricGroup":{"citations":[],"captures":[],"mentions":[],"socialMedia":[]},"isLoading":false,"error":false,"hasMetrics":false},"preview":{"content":[{"#name":"introduction","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"sec1","role":"introduction","view":"all"},"$$":[{"#name":"label","_":"1"},{"#name":"section-title","$":{"id":"d1e9225"},"_":"Introduction"},{"#name":"para","$":{"id":"d1e9227","view":"all"},"_":"Resting-state functional magnetic resonance imaging (rs-fMRI) focuses on measuring low-frequency blood-oxygen-level-dependent (BOLD) signals during a resting state without performing specific tasks, and has become an essential tool in neuroimaging (Shirer et al., 2015, Amemiya et al., 2016). The functional connectivity (FC) described by rs-fMRI can capture brain activity patterns and relationships between brain regions-of-interest (ROIs), which is increasingly used to explore the pathological mechanisms and conduct automated diagnosis of brain diseases such as major depressive disorder (MDD) and autism spectrum disorder (ASD) (Dai et al., 2023, Nebel et al., 2022, Mao et al., 2019, Fang et al., 2023). With the advancement of machine learning and deep learning, an increasing number of technologies are being developed for fMRI biomarker discovery and automated brain disorder detection (Bondi et al., 2023, Hou et al., 2023, Hebling Vieira et al., 2021, Wang et al., 2024). However, learning models typically need substantial annotated samples to achieve good generalization performance (Ingalhalikar et al., 2021, Cui et al., 2023, Wang et al., 2023, Weiner et al., 2013)."},{"#name":"para","$":{"id":"d1e9250","view":"all"},"$$":[{"#name":"__text__","_":"Self-supervised learning such as graph contrastive learning offers a promising solution to this issue without the requirement for labeled data, leveraging its strong transferability to address the small-sample-size problem (Fedorov et al., 2024). Graph augmentation is generally a crucial component within graph contrastive learning frameworks (Demirel and Holz, 2024). Many fMRI-based contrastive learning studies focus on augmenting fMRI time series using various techniques ("},{"#name":"italic","_":"e.g."},{"#name":"__text__","_":", window slicing and window warping), which may damage the information embedded in the original BOLD signals and thereby impede subsequent fMRI feature extraction (Wang et al., 2022, Tang et al., 2022, Bijsterbosch et al., 2017). Several state-of-the-art (SOTA) graph augmentation strategies, such as GNN-based methods used in Auto-GCL (Yin et al., 2022) and AD-GCL (Suresh et al., 2021), are still difficult to generate high-quality samples since their generators are not specifically tailored for graph generation. As a powerful deep generative model, diffusion models have seen extensive applications across diverse fields with unparalleled performance, including image synthesis, molecule design, and medical data analysis (Yang et al., 2023, Wu et al., 2024). However, a few studies investigate the diffusion model to implement data augmentation based on brain functional connectivity networks (FCNs) and integrate it with contrastive learning for brain disease detection."}]},{"#name":"para","$":{"id":"d1e9287","view":"all"},"$$":[{"#name":"__text__","_":"In this paper, we propose a self-supervised graph contrastive learning framework with diffusion augmentation (GCDA) for fMRI analysis and brain disorder detection. The GCDA consists of a "},{"#name":"italic","_":"pretext model"},{"#name":"__text__","_":" that learns general and transferable fMRI features and a "},{"#name":"italic","_":"task-specific model"},{"#name":"__text__","_":" that aims to fine-tune the pretext model to cater to downstream tasks. Specifically, the pretext model contains three components: (1) a graph construction module, (2) a graph diffusion augmentation (GDA) module, and (3) a graph contrastive learning module. First, we utilize the graph construction module to build functional connectivity networks/graphs based on fMRI data. The graphs are then passed through the GDA module, which perturbs the edges and nodes of the graph, thus preserving the integrity of the original BOLD signal while being able to generate high-quality augmented graphs. Then, two graph isomorphism networks (GINs) with shared parameters are employed to extract general fMRI features in a self-supervised contrastive learning manner. Note that the pretext model is optimized based on unlabeled fMRI data, eliminating the tedious annotation procedure. The task-specific model is proposed to adjust the well-trained parameters of the pretext model to adapt to downstream tasks in a supervised task-oriented manner. We assess the proposed GCDA on two datasets with rs-fMRI data from a total of 1230 subjects, and the experimental results indicate that our GCDA surpasses several SOTA approaches in automatically diagnosing two types of brain diseases."}]},{"#name":"para","$":{"id":"d1e9295","view":"all"},"_":"The main contributions of this work are outlined below."},{"#name":"para","$":{"id":"d1e9297","view":"all"},"$$":[{"#name":"list","$":{"id":"d1e9299"},"$$":[{"#name":"list-item","$":{"id":"lst1"},"$$":[{"#name":"label","_":"•"},{"#name":"para","$":{"id":"d1e9303","view":"all"},"_":"A self-supervised graph contrastive learning framework with diffusion augmentation is developed for fMRI analysis and brain disease detection, which effectively tackles the small-sample-size problem in fMRI studies."}]},{"#name":"list-item","$":{"id":"lst2"},"$$":[{"#name":"label","_":"•"},{"#name":"para","$":{"id":"d1e9308","view":"all"},"_":"A novel graph diffusion augmentation strategy is designed to modify node and edge features within a brain graph, which greatly helps preserve the integrity of the original signals and facilitate effective fMRI feature extraction."}]},{"#name":"list-item","$":{"id":"lst3"},"$$":[{"#name":"label","_":"•"},{"#name":"para","$":{"id":"d1e9313","view":"all"},"_":"Experiments on two rs-fMRI datasets suggest the superiority of our method compared to several state-of-the-art approaches in brain disease diagnosis. Moreover, our method aids in identifying functional connectivity abnormalities and brain regions associated with diseases, thus facilitating fMRI-based brain disease analysis in clinical practice."}]}]}]},{"#name":"para","$":{"id":"d1e9315","view":"all"},"_":"The remainder of this work is organized as follows. We review related studies in Section 2. In Section 3, we introduce studied materials and the proposed method. In Section 4, we present experimental settings and experimental results. In Section 5, we discuss several key components of the proposed method, as well as several limitations of the current work. Finally, we conclude this paper in Section 6."}]}]},{"#name":"section","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"sec2","view":"all"},"$$":[{"#name":"label","_":"2"},{"#name":"section-title","$":{"id":"d1e9346"},"_":"Related work"},{"#name":"section","$":{"id":"sec2.1","view":"all"},"$$":[{"#name":"label","_":"2.1"},{"#name":"section-title","$":{"id":"d1e9351"},"_":"Self-supervised learning for fMRI analysis"},{"#name":"para","$":{"id":"d1e9353","view":"all"},"_":"Self-supervised learning is a learning paradigm where the model uses the intrinsic structure or features within the data to generate labels or supervised signals. It then learns to extract meaningful information by using these generated labels as training targets (Liu et al., 2021). This learning paradigm does not require annotation and plays a crucial role in advancing fMRI analysis as well as brain disorder diagnosis. For instance, Wen et al. (2023) developed a self-supervised learning"}]}]}]},{"#name":"section","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"sec3","view":"all"},"$$":[{"#name":"label","_":"3"},{"#name":"section-title","$":{"id":"d1e9446"},"_":"Materials and method"},{"#name":"section","$":{"id":"sec3.1","view":"all"},"$$":[{"#name":"label","_":"3.1"},{"#name":"section-title","$":{"id":"d1e9451"},"_":"Materials and data preprocessing"},{"#name":"para","$":{"id":"d1e9453","view":"all"},"$$":[{"#name":"__text__","_":"Two datasets with rs-fMRI scans are used in the experiments, including (1) REST-meta-MDD Consortium (REST-MDD)"},{"#name":"sup","$":{"loc":"post"},"_":"1"},{"#name":"footnote","$":{"id":"fn1"},"$$":[{"#name":"label","_":"1"},{"#name":"note-para","$":{"id":"d1e9461","view":"all"},"$$":[{"#name":"inter-ref","$":{"id":"interref1","href":"http://rfmri.org/REST-meta-MDD","type":"simple"},"_":"http://rfmri.org/REST-meta-MDD"},{"#name":"__text__","_":"."}]}]},{"#name":"__text__","_":" and (2) Autism Brain Imaging Data Exchange (ABIDE)."},{"#name":"sup","$":{"loc":"post"},"_":"2"},{"#name":"footnote","$":{"id":"fn2"},"$$":[{"#name":"label","_":"2"},{"#name":"note-para","$":{"id":"d1e9472","view":"all"},"$$":[{"#name":"inter-ref","$":{"id":"interref2","href":"http://fcon_1000.projects.nitrc.org/indi/abide","type":"simple"},"_":"http://fcon_1000.projects.nitrc.org/indi/abide"},{"#name":"__text__","_":"."}]}]},{"#name":"__text__","_":" For each dataset, we use the top three largest sites in the experiments. Specifically, the largest site is utilized to train the pretext model to acquire general fMRI feature representations, and the remaining sites are utilized to fine-tune the"}]}]}]}]},{"#name":"section","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"sec4","view":"all"},"$$":[{"#name":"label","_":"4"},{"#name":"section-title","$":{"id":"d1e14144"},"_":"Experiments"},{"#name":"section","$":{"id":"sec4.1","view":"all"},"$$":[{"#name":"label","_":"4.1"},{"#name":"section-title","$":{"id":"d1e14149"},"_":"Experimental settings"},{"#name":"para","$":{"id":"d1e14151","view":"all"},"$$":[{"#name":"__text__","_":"In this work, we conduct cross-site brain disease classification, where we first pre-train a pretext model using one imaging site and then fine-tune it on other sites. Two groups of experiments are performed, which are detailed as follows. (1) We perform MDD vs. HC classification using REST-MDD dataset. The pretext model is trained on the largest site (Site "},{"#name":"math","$":{"altimg":"si1002.svg","display":"inline","id":"d1e14154"},"$$":[{"#name":"mrow","$$":[{"#name":"mn","_":"20"}]}]},{"#name":"__text__","_":"), and Site "},{"#name":"math","$":{"altimg":"si1004.svg","display":"inline","id":"d1e14160"},"$$":[{"#name":"mn","_":"1"}]},{"#name":"__text__","_":" and Site "},{"#name":"math","$":{"altimg":"si15.svg","display":"inline","id":"d1e14165"},"$$":[{"#name":"mrow","$$":[{"#name":"mn","_":"21"}]}]},{"#name":"__text__","_":" are used for model fine-tuning and test, respectively. (2) We perform ASD vs. HC classification on ABIDE"}]}]}]}]},{"#name":"section","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"sec5","role":"discussion","view":"all"},"$$":[{"#name":"label","_":"5"},{"#name":"section-title","$":{"id":"d1e14713"},"_":"Discussion"},{"#name":"section","$":{"id":"sec5.1","view":"all"},"$$":[{"#name":"label","_":"5.1"},{"#name":"section-title","$":{"id":"d1e14718"},"_":"Ablation study"},{"#name":"para","$":{"id":"d1e14720","view":"all"},"$$":[{"#name":"__text__","_":"To investigate the importance of our introduced GDA module, we compare GCDA with its three variants, "},{"#name":"italic","_":"i.e."},{"#name":"__text__","_":", "},{"#name":"bold","_":"GCDAw/oNODE"},{"#name":"__text__","_":", "},{"#name":"bold","_":"GCDAw/oEDGE"},{"#name":"__text__","_":", and "},{"#name":"bold","_":"GCDAw/oT"},{"#name":"__text__","_":". In GCDAw/oNODE, only the diffusion of edge features is used during the forward process, while the step of adding noise to node features is removed. In GCDAw/oEDGE, only the diffusion of node features is utilized, while the noise addition on edge features is omitted. The GCDAw/oT method discards the denoising neural network and only performs diffusion "}]}]}]}]},{"#name":"section","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"sec6","role":"conclusion","view":"all"},"$$":[{"#name":"label","_":"6"},{"#name":"section-title","$":{"id":"d1e16130"},"_":"Conclusion"},{"#name":"para","$":{"id":"d1e16132","view":"all"},"_":"This work presents a self-supervised graph contrastive learning framework with diffusion augmentation (GCDA) for functional MRI analysis. The GCDA comprises a pretext model for pre-training and a task-specific model for fine-tuning. In the pretext model, we first augment each brain functional connectivity network derived from fMRI through a graph diffusion augmentation module, and then use two graph isomorphism networks with shared parameters to extract features in a self-supervised contrastive "}]}]},{"#name":"section","$$":[{"#name":"section","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"d1e16134","view":"all"},"$$":[{"#name":"section-title","$":{"id":"d1e16135"},"_":"CRediT authorship contribution statement"},{"#name":"para","$":{"id":"d1e16137","view":"all"},"$$":[{"#name":"bold","_":"Xiaochuan Wang:"},{"#name":"__text__","_":" Writing – original draft, Software, Methodology. "},{"#name":"bold","_":"Yuqi Fang:"},{"#name":"__text__","_":" Writing – review & editing. "},{"#name":"bold","_":"Qianqian Wang:"},{"#name":"__text__","_":" Writing – review & editing. "},{"#name":"bold","_":"Pew-Thian Yap:"},{"#name":"__text__","_":" Writing – review & editing. "},{"#name":"bold","_":"Hongtu Zhu:"},{"#name":"__text__","_":" Writing – review & editing. "},{"#name":"bold","_":"Mingxia Liu:"},{"#name":"__text__","_":" Writing – review & editing, Validation, Supervision, Conceptualization."}]}]}]},{"#name":"section","$$":[{"#name":"conflict-of-interest","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"coi1","view":"all"},"$$":[{"#name":"section-title","$":{"id":"d1e16157"},"_":"Declaration of competing interest"},{"#name":"para","$":{"id":"d1e16159","view":"all"},"_":"The authors declare that they have no known competing financial interests or personal relationships that could have appeared to influence the work reported in this paper."}]}]},{"#name":"section","$$":[{"#name":"acknowledgment","$":{"xmlns:ce":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"d1e16161","view":"all"},"$$":[{"#name":"section-title","$":{"id":"d1e16162"},"_":"Acknowledgments"},{"#name":"para","$":{"id":"d1e16164","view":"all"},"$$":[{"#name":"__text__","_":"The research of P. Yap, H. Zhu and M. Liu was supported in part by the "},{"#name":"grant-sponsor","$":{"id":"GS1","sponsor-id":"http://dx.doi.org/10.13039/100000002","role":"http://www.elsevier.com/xml/linking-roles/grant-sponsor","type":"simple"},"_":"National Institutes of Health (NIH), United States"},{"#name":"__text__","_":" , under award numbers "},{"#name":"grant-number","$":{"id":"d1e16173","refid":"GS1"},"_":"AG073297"},{"#name":"__text__","_":", "},{"#name":"grant-number","$":{"id":"d1e16176","refid":"GS1"},"_":"AG082938"},{"#name":"__text__","_":", "},{"#name":"grant-number","$":{"id":"d1e16180","refid":"GS1"},"_":"EB035160"},{"#name":"__text__","_":", and "},{"#name":"grant-number","$":{"id":"d1e16183","refid":"GS1"},"_":"NS134849"},{"#name":"__text__","_":"."}]}]}]}],"floats":[],"footnotes":[{"#name":"footnote","$":{"id":"fn1"},"$$":[{"#name":"label","_":"1"},{"#name":"note-para","$":{"id":"d1e9461","view":"all"},"$$":[{"#name":"inter-ref","$":{"id":"interref1","href":"http://rfmri.org/REST-meta-MDD","type":"simple"},"_":"http://rfmri.org/REST-meta-MDD"},{"#name":"__text__","_":"."}]}]},{"#name":"footnote","$":{"id":"fn2"},"$$":[{"#name":"label","_":"2"},{"#name":"note-para","$":{"id":"d1e9472","view":"all"},"$$":[{"#name":"inter-ref","$":{"id":"interref2","href":"http://fcon_1000.projects.nitrc.org/indi/abide","type":"simple"},"_":"http://fcon_1000.projects.nitrc.org/indi/abide"},{"#name":"__text__","_":"."}]}]}],"attachments":[]},"rawtext":"","recommendations":{"articles":[{"pii":"S136184152400375X","doi":"10.1016/j.media.2024.103448","journalTitle":"Medical Image Analysis","publicationYear":"2025","publicationDate":"2025-04-01","volumeSupText":"Volume 101","articleNumber":"103448","pageRange":"103448","trace-token":"AAAAQGXIqwOoU49vlm_PnlcrBlrF2Vt8aUIqRj5rqSf7GljK1Gp-1wFKso3eF7fB-pOZfj_yIV-37rWUynvhjn_pO1e4U64O-kwAQV5I6NivckYrXaYo2w","authors":{"content":[{"#name":"author-group","$":{"id":"d1e3372"},"$$":[{"#name":"author","$":{"author-id":"S136184152400375X-70dc47c270046fee27e48a7a313c8730","id":"au000001"},"$$":[{"#name":"given-name","_":"Haozhe"},{"#name":"surname","_":"Xu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/visualization"},"_":"Visualization"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e3397","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e3400","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]},{"#name":"cross-ref","$":{"id":"d1e3403","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e3406","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]},{"#name":"cross-ref","$":{"id":"d1e3409","refid":"fn1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"1"}]}]},{"#name":"author","$":{"author-id":"S136184152400375X-bb2b3cafd5745c7370b838bf5c10cd1d","id":"au000002"},"$$":[{"#name":"given-name","_":"Jian"},{"#name":"surname","_":"Wang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/visualization"},"_":"Visualization"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"cross-ref","$":{"id":"d1e3429","refid":"aff5"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"e"}]},{"#name":"cross-ref","$":{"id":"d1e3432","refid":"fn1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"1"}]}]},{"#name":"author","$":{"author-id":"S136184152400375X-3a67670ee936ba8ab1cbb0b7bee36036","id":"au000003"},"$$":[{"#name":"given-name","_":"Qianjin"},{"#name":"surname","_":"Feng"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"cross-ref","$":{"id":"d1e3446","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e3449","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e3452","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]}]},{"#name":"author","$":{"author-id":"S136184152400375X-f8bc699923d87803eff77a1bba50b186","id":"au000004"},"$$":[{"#name":"given-name","_":"Yu"},{"#name":"surname","_":"Zhang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e3479","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e3482","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e3485","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]},{"#name":"cross-ref","$":{"id":"d1e3488","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea1","type":"email","href":"mailto:yuzhang@smu.edu.cn"},"_":"yuzhang@smu.edu.cn"}]},{"#name":"author","$":{"author-id":"S136184152400375X-c02f244755591a853224810f05669206","id":"au000005"},"$$":[{"#name":"given-name","_":"Zhenyuan"},{"#name":"surname","_":"Ning"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e3517","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e3520","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e3523","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]},{"#name":"cross-ref","$":{"id":"d1e3526","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:jonnyning@foxmail.com"},"_":"jonnyning@foxmail.com"}]},{"#name":"affiliation","$":{"affiliation-id":"S136184152400375X-1215a5bc31365352798326ca8da960fc","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"School of Biomedical Engineering, Southern Medical University, Guangzhou 510515, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biomedical Engineering, Southern Medical University"},{"#name":"city","_":"Guangzhou"},{"#name":"postal-code","_":"510515"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs59"},"_":"School of Biomedical Engineering, Southern Medical University, Guangzhou 510515, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S136184152400375X-3a20e7b5eb0210e7e486a40fbcd7a223","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"Department of Radiotherapy, State Key Laboratory of Oncology in South China, Guangdong Provincial Clinical Research Center for Cancer, Sun Yat-sen University Cancer Center, Guangzhou 510515, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Radiotherapy, State Key Laboratory of Oncology in South China, Guangdong Provincial Clinical Research Center for Cancer, Sun Yat-sen University Cancer Center"},{"#name":"city","_":"Guangzhou"},{"#name":"postal-code","_":"510515"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs60"},"_":"o=Department of Radiotherapy, State Key Laboratory of Oncology in South China, Guangdong Provincial Clinical Research Center for Cancer, Sun Yat-sen University Cancer Center, c=Guangzhou,cp=, p=510515, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S136184152400375X-df21ed233a9f592f63867a8569b8204f","id":"aff3"},"$$":[{"#name":"label","_":"c"},{"#name":"textfn","_":"Guangdong Provincial Key Laboratory of Medical Image Processing, Southern Medical University, Guangzhou 510515, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Guangdong Provincial Key Laboratory of Medical Image Processing, Southern Medical University"},{"#name":"city","_":"Guangzhou"},{"#name":"postal-code","_":"510515"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs61"},"_":"Guangdong Provincial Key Laboratory of Medical Image Processing, Southern Medical University, Guangzhou 510515, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S136184152400375X-3584625b7d26a4da15f8daa6f56bdb57","id":"aff4"},"$$":[{"#name":"label","_":"d"},{"#name":"textfn","_":"Guangdong Province Engineering Laboratory for Medical Imaging and Diagnostic Technology, Southern Medical University, Guangzhou 510515, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Guangdong Province Engineering Laboratory for Medical Imaging and Diagnostic Technology, Southern Medical University"},{"#name":"city","_":"Guangzhou"},{"#name":"postal-code","_":"510515"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs62"},"_":"Guangdong Province Engineering Laboratory for Medical Imaging and Diagnostic Technology, Southern Medical University, Guangzhou 510515, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S136184152400375X-41c3d25f02d506b8cdec46885014699b","id":"aff5"},"$$":[{"#name":"label","_":"e"},{"#name":"textfn","_":"Department of Radiation Oncology, Nanfang Hospital, Southern Medical University, Guangzhou, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Radiation Oncology, Nanfang Hospital, Southern Medical University"},{"#name":"city","_":"Guangzhou"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs63"},"_":"Department of Radiation Oncology, Nanfang Hospital, Southern Medical University, Guangzhou, China"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding authors at: School of Biomedical Engineering, Southern Medical University, Guangzhou, China."},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biomedical Engineering, Southern Medical University"},{"#name":"city","_":"Guangzhou"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]}]},{"#name":"footnote","$":{"id":"fn1"},"$$":[{"#name":"label","_":"1"},{"#name":"note-para","$":{"id":"d1e3625","view":"all"},"_":"The two authors contribute equally to this work."}]}]}],"floats":[],"footnotes":[{"#name":"footnote","$":{"id":"fn1"},"$$":[{"#name":"label","_":"1"},{"#name":"note-para","$":{"id":"d1e3625","view":"all"},"_":"The two authors contribute equally to this work."}]}],"attachments":[]},"lastAuthor":{"content":[{"#name":"author","$":{"author-id":"S136184152400375X-c02f244755591a853224810f05669206","id":"au000005"},"$$":[{"#name":"given-name","_":"Zhenyuan"},{"#name":"surname","_":"Ning"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e3517","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e3520","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e3523","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]},{"#name":"cross-ref","$":{"id":"d1e3526","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:jonnyning@foxmail.com"},"_":"jonnyning@foxmail.com"}]}],"floats":[],"footnotes":[],"attachments":[]},"title":{"content":[{"#name":"title","$":{"id":"d1e3369"},"_":"Domain-specific information preservation for Alzheimer’s disease diagnosis with incomplete multi-modality neuroimages"}],"floats":[],"footnotes":[],"attachments":[]},"openArchive":false,"openAccess":false,"document-subtype":"fla","content-family":"serial","contentType":"JL","entitlementType":"","pdf":{"urlType":null},"iss-first":"","vol-first":"101","isThirdParty":false,"language":"en","issn-primary-unformatted":"13618415","issn-primary-formatted":"1361-8415"},{"pii":"S1361841524003244","doi":"10.1016/j.media.2024.103399","journalTitle":"Medical Image Analysis","publicationYear":"2025","publicationDate":"2025-02-01","volumeSupText":"Volume 100","articleNumber":"103399","pageRange":"103399","trace-token":"AAAAQGXIqwOoU49vlm_PnlcrBlrF2Vt8aUIqRj5rqSf7GljK1L0eLZVYP7mMKTT8fbXRrGUvmkeiWwruQAEgzrPVgOn1T2eMeINzOjsDhO-GR1esKpXHoQ","authors":{"content":[{"#name":"author-group","$":{"id":"d1e1232"},"$$":[{"#name":"author","$":{"author-id":"S1361841524003244-354673a71995daf45932bdea37a7ab7e","id":"au000001"},"$$":[{"#name":"given-name","_":"Luhao"},{"#name":"surname","_":"Sun"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1246","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1249","refid":"fn1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"1"}]}]},{"#name":"author","$":{"author-id":"S1361841524003244-e83d82428ebbb658bcd2f4e9331a1f84","id":"au000002","orcid":"0009-0003-4602-8420"},"$$":[{"#name":"given-name","_":"Bowen"},{"#name":"surname","_":"Han"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1263","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]},{"#name":"cross-ref","$":{"id":"d1e1266","refid":"fn1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"1"}]}]},{"#name":"author","$":{"author-id":"S1361841524003244-d30cb3f092f15f6c01a8e58731733a7c","id":"au000003"},"$$":[{"#name":"given-name","_":"Wenzong"},{"#name":"surname","_":"Jiang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1278","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]}]},{"#name":"author","$":{"author-id":"S1361841524003244-df3df975c57c5955757eeaa7118b18d4","id":"au000004","orcid":"0000-0002-5388-9080"},"$$":[{"#name":"given-name","_":"Weifeng"},{"#name":"surname","_":"Liu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1296","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]}]},{"#name":"author","$":{"author-id":"S1361841524003244-471ad4882968e1ae71e89eb4ece6c348","id":"au000005","orcid":"0000-0002-1408-5514"},"$$":[{"#name":"given-name","_":"Baodi"},{"#name":"surname","_":"Liu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"cross-ref","$":{"id":"d1e1312","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]}]},{"#name":"author","$":{"author-id":"S1361841524003244-d26c1d8595ed659901dd9f06775a4157","id":"au000006"},"$$":[{"#name":"given-name","_":"Dapeng"},{"#name":"surname","_":"Tao"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1328","refid":"aff5"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"e"}]},{"#name":"cross-ref","$":{"id":"d1e1331","refid":"aff6"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"f"}]}]},{"#name":"author","$":{"author-id":"S1361841524003244-2186ba20690dd23c4886d3ee611aa374","id":"au000007"},"$$":[{"#name":"given-name","_":"Zhiyong"},{"#name":"surname","_":"Yu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1349","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1352","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea1","type":"email","href":"mailto:zyyu@sdfmu.edu.cn"},"_":"zyyu@sdfmu.edu.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003244-c1d1c746e0eb6fafef2189dd865567b0","id":"au000008","orcid":"0000-0002-0112-7535"},"$$":[{"#name":"given-name","_":"Chao"},{"#name":"surname","_":"Li"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1368","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1371","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:lichao19890305@126.com"},"_":"lichao19890305@126.com"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003244-23098390fe6a38aaa296397a826bf5dd","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"Breast Cancer Center, Shandong Cancer Hospital and Institute, Shandong First Medical University and Shandong Academy of Medical Sciences, Jinan 250117, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Breast Cancer Center, Shandong Cancer Hospital and Institute, Shandong First Medical University and Shandong Academy of Medical Sciences"},{"#name":"city","_":"Jinan"},{"#name":"postal-code","_":"250117"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs70"},"_":"Breast Cancer Center, Shandong Cancer Hospital and Institute, Shandong First Medical University and Shandong Academy of Medical Sciences, Jinan 250117, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003244-a66288dde3aec83ba9cf20d76a83a8f5","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"School of Computer Science and Technology, Tongji University, Shanghai 201804, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Computer Science and Technology, Tongji University"},{"#name":"city","_":"Shanghai"},{"#name":"postal-code","_":"201804"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs71"},"_":"School of Computer Science and Technology, Tongji University, Shanghai 201804, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003244-dee564041b7e9340998f0075bd54616b","id":"aff3"},"$$":[{"#name":"label","_":"c"},{"#name":"textfn","_":"The College of Control Science and Engineering, China University of Petroleum (East China), Qingdao 266580, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"The College of Control Science and Engineering, China University of Petroleum (East China)"},{"#name":"city","_":"Qingdao"},{"#name":"postal-code","_":"266580"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs72"},"_":"The College of Control Science and Engineering, China University of Petroleum (East China), Qingdao 266580, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003244-50d0e218d222ad89373a660d4c83a1dc","id":"aff4"},"$$":[{"#name":"label","_":"d"},{"#name":"textfn","_":"The College of Oceanography and Space Informatics, China University of Petroleum (East China), Qingdao 266580, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"The College of Oceanography and Space Informatics, China University of Petroleum (East China)"},{"#name":"city","_":"Qingdao"},{"#name":"postal-code","_":"266580"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs73"},"_":"The College of Oceanography and Space Informatics, China University of Petroleum (East China), Qingdao 266580, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003244-a5742f09b4cfd0625e7b637ced6960d2","id":"aff5"},"$$":[{"#name":"label","_":"e"},{"#name":"textfn","_":"The School of Information Science and Engineering, Yunnan University, Yunnan 650504, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"The School of Information Science and Engineering, Yunnan University"},{"#name":"city","_":"Yunnan"},{"#name":"postal-code","_":"650504"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs74"},"_":"The School of Information Science and Engineering, Yunnan University, Yunnan 650504, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003244-bc3d55c0c6b7b51c98471b2795d4e9b2","id":"aff6"},"$$":[{"#name":"label","_":"f"},{"#name":"textfn","_":"Yunnan United Vision Technology Co., Ltd., Yunnan 650504, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Yunnan United Vision Technology Co., Ltd."},{"#name":"city","_":"Yunnan"},{"#name":"postal-code","_":"650504"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs75"},"_":"Yunnan United Vision Technology Co., Ltd., Yunnan 650504, China"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding authors."}]},{"#name":"footnote","$":{"id":"fn1"},"$$":[{"#name":"label","_":"1"},{"#name":"note-para","$":{"id":"d1e1481","view":"all"},"_":"Luhao Sun and Bowen Han are co-first authors."}]}]}],"floats":[],"footnotes":[{"#name":"footnote","$":{"id":"fn1"},"$$":[{"#name":"label","_":"1"},{"#name":"note-para","$":{"id":"d1e1481","view":"all"},"_":"Luhao Sun and Bowen Han are co-first authors."}]}],"attachments":[]},"lastAuthor":{"content":[{"#name":"author","$":{"author-id":"S1361841524003244-c1d1c746e0eb6fafef2189dd865567b0","id":"au000008","orcid":"0000-0002-0112-7535"},"$$":[{"#name":"given-name","_":"Chao"},{"#name":"surname","_":"Li"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1368","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1371","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:lichao19890305@126.com"},"_":"lichao19890305@126.com"}]}],"floats":[],"footnotes":[],"attachments":[]},"title":{"content":[{"#name":"title","$":{"id":"d1e1229"},"_":"Multi-scale region selection network in deep features for full-field mammogram classification"}],"floats":[],"footnotes":[],"attachments":[]},"openArchive":false,"openAccess":true,"document-subtype":"fla","content-family":"serial","contentType":"JL","entitlementType":"","pdf":{"urlType":null},"iss-first":"","vol-first":"100","isThirdParty":false,"language":"en","issn-primary-unformatted":"13618415","issn-primary-formatted":"1361-8415"},{"pii":"S1361841524003499","doi":"10.1016/j.media.2024.103424","journalTitle":"Medical Image Analysis","publicationYear":"2025","publicationDate":"2025-04-01","volumeSupText":"Volume 101","articleNumber":"103424","pageRange":"103424","trace-token":"AAAAQGXIqwOoU49vlm_PnlcrBlrF2Vt8aUIqRj5rqSf7GljK6P8KGeXYlekHqpB1cpv33h4jfpMt62IXBWwmqj5i3KaIj2_npKNpXcowWco0VDXTFiVowg","authors":{"content":[{"#name":"author-group","$":{"id":"d1e762"},"$$":[{"#name":"author","$":{"author-id":"S1361841524003499-781355ea6722bcdbc0ca91ec276f15cd","id":"au000001"},"$$":[{"#name":"given-name","_":"Jing"},{"#name":"surname","_":"Ke"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/resources"},"_":"Resources"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/project-administration"},"_":"Project administration"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e787","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e790","refid":"aff9"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"i"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea1","type":"email","href":"mailto:kejing@sjtu.edu.cn"},"_":"kejing@sjtu.edu.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003499-f7cfa4649083337ac15aa0ce8eb40578","id":"au000002","orcid":"0000-0003-3162-3502"},"$$":[{"#name":"given-name","_":"Yijin"},{"#name":"surname","_":"Zhou"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/visualization"},"_":"Visualization"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"cross-ref","$":{"id":"d1e808","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]},{"#name":"cross-ref","$":{"id":"d1e811","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:708972751@sjtu.edu.cn"},"_":"708972751@sjtu.edu.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003499-2031ef2708480aba25d25c771bcacdc6","id":"au000003","orcid":"0000-0001-7866-3339"},"$$":[{"#name":"given-name","_":"Yiqing"},{"#name":"surname","_":"Shen"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e827","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e830","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea3","type":"email","href":"mailto:yshen92@jhu.edu"},"_":"yshen92@jhu.edu"}]},{"#name":"author","$":{"author-id":"S1361841524003499-94dd7b7ac7171ee156611459f45ccab0","id":"au000004"},"$$":[{"#name":"given-name","_":"Yi"},{"#name":"surname","_":"Guo"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"cross-ref","$":{"id":"d1e842","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea4","type":"email","href":"mailto:y.guo@westernsydney.com.au"},"_":"y.guo@westernsydney.com.au"}]},{"#name":"author","$":{"author-id":"S1361841524003499-287ec4b7d8513d8b2b9f2f9df916e438","id":"au000005"},"$$":[{"#name":"given-name","_":"Ning"},{"#name":"surname","_":"Liu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"cross-ref","$":{"id":"d1e854","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e857","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea5","type":"email","href":"mailto:ningliu@sjtu.edu.cn"},"_":"ningliu@sjtu.edu.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003499-de66783b5c2a2719e7605e4c4fb08aa2","id":"au000006"},"$$":[{"#name":"given-name","_":"Xiaodan"},{"#name":"surname","_":"Han"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"cross-ref","$":{"id":"d1e869","refid":"aff5"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"e"}]},{"#name":"cross-ref","$":{"id":"d1e872","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea6","type":"email","href":"mailto:han.xiaodan@zs-hospital.sh.cn"},"_":"han.xiaodan@zs-hospital.sh.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003499-93ee8d34c49327e278be89df1c0bead5","id":"au000007"},"$$":[{"#name":"given-name","_":"Dinggang"},{"#name":"surname","_":"Shen"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"cross-ref","$":{"id":"d1e884","refid":"aff6"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"f"}]},{"#name":"cross-ref","$":{"id":"d1e887","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]},{"#name":"cross-ref","$":{"id":"d1e890","refid":"aff8"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"h"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea7","type":"email","href":"mailto:dgshen@shanghaitech.edu.cn"},"_":"dgshen@shanghaitech.edu.cn"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-03e4741f5f9af8562cb0cd115fd9403c","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University, Shanghai, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University"},{"#name":"city","_":"Shanghai"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs47"},"_":"School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University, Shanghai, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-ed44c72b30d59f5a336242ea9bb7d991","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"School of Mathematical Sciences, Shanghai Jiao Tong University, Shanghai, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Mathematical Sciences, Shanghai Jiao Tong University"},{"#name":"city","_":"Shanghai"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs48"},"_":"School of Mathematical Sciences, Shanghai Jiao Tong University, Shanghai, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-64f2de53a45b9662b704697bdb10eaff","id":"aff3"},"$$":[{"#name":"label","_":"c"},{"#name":"textfn","_":"Department of Computer Science, Johns Hopkins University, Baltimore, MD, USA"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Computer Science, Johns Hopkins University"},{"#name":"city","_":"Baltimore"},{"#name":"state","_":"MD"},{"#name":"country","$":{"iso3166-1-alpha-3":"USA"},"_":"USA"}]},{"#name":"source-text","$":{"id":"afs49"},"_":"Department of Computer Science, Johns Hopkins University, Baltimore, Maryland, USA"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-dba6a157bc4e24885c3bc3f1723131c5","id":"aff4"},"$$":[{"#name":"label","_":"d"},{"#name":"textfn","_":"School of Computer, Data and Mathematical Sciences, Western Sydney University, Sydney, Australia"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Computer, Data and Mathematical Sciences, Western Sydney University"},{"#name":"city","_":"Sydney"},{"#name":"country","$":{"iso3166-1-alpha-3":"AUS"},"_":"Australia"}]},{"#name":"source-text","$":{"id":"afs50"},"_":"School of Computer, Data and Mathematical Sciences, Western Sydney University, Sydney, Australia"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-1d91eeb9a5622b7ef999dbf916dfca58","id":"aff5"},"$$":[{"#name":"label","_":"e"},{"#name":"textfn","_":"Department of Anaesthesiology, Zhongshan Hospital, Fudan University, Shanghai, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Anaesthesiology, Zhongshan Hospital, Fudan University"},{"#name":"city","_":"Shanghai"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs51"},"_":"Department of Anaesthesiology, Zhongshan Hospital, Fudan University, Shanghai, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-441bf8b3d22c1fbbd6107a4d89666ffa","id":"aff6"},"$$":[{"#name":"label","_":"f"},{"#name":"textfn","_":"School of Biomedical Engineering & State Key Laboratory of Advanced Medical Materials and Devices, ShanghaiTech University, Shanghai, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biomedical Engineering & State Key Laboratory of Advanced Medical Materials and Devices, ShanghaiTech University"},{"#name":"city","_":"Shanghai"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs52"},"_":"o=School of Biomedical Engineering & State Key Laboratory of Advanced Medical Materials and Devices, ShanghaiTech University, c=Shanghai, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-08ae42a0d9b6807c5afb855198bb03d4","id":"aff7"},"$$":[{"#name":"label","_":"g"},{"#name":"textfn","_":"Shanghai United Imaging Intelligence Co., Ltd., Shanghai, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Shanghai United Imaging Intelligence Co., Ltd."},{"#name":"city","_":"Shanghai"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs53"},"_":"Shanghai United Imaging Intelligence Co., Ltd., Shanghai, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-1bc2745b6d26f5e35022d2013faf768e","id":"aff8"},"$$":[{"#name":"label","_":"h"},{"#name":"textfn","_":"Shanghai Clinical Research and Trial Center, Shanghai, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Shanghai Clinical Research and Trial Center"},{"#name":"city","_":"Shanghai"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs54"},"_":"Shanghai Clinical Research and Trial Center, Shanghai, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003499-551a9ab0a057eb8dba17c10182c6385d","id":"aff9"},"$$":[{"#name":"label","_":"i"},{"#name":"textfn","_":"School of Computer Science and Engineering, University of New South Wales, Australia"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Computer Science and Engineering, University of New South Wales"},{"#name":"country","$":{"iso3166-1-alpha-3":"AUS"},"_":"Australia"}]},{"#name":"source-text","$":{"id":"afs55"},"_":"School of Computer Science and Engineering, University of New South Wales, Australia"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding authors."}]}]}],"floats":[],"footnotes":[],"attachments":[]},"lastAuthor":{"content":[{"#name":"author","$":{"author-id":"S1361841524003499-93ee8d34c49327e278be89df1c0bead5","id":"au000007"},"$$":[{"#name":"given-name","_":"Dinggang"},{"#name":"surname","_":"Shen"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"cross-ref","$":{"id":"d1e884","refid":"aff6"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"f"}]},{"#name":"cross-ref","$":{"id":"d1e887","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]},{"#name":"cross-ref","$":{"id":"d1e890","refid":"aff8"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"h"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea7","type":"email","href":"mailto:dgshen@shanghaitech.edu.cn"},"_":"dgshen@shanghaitech.edu.cn"}]}],"floats":[],"footnotes":[],"attachments":[]},"title":{"content":[{"#name":"title","$":{"id":"d1e759"},"_":"Learnable color space conversion and fusion for stain normalization in pathology images"}],"floats":[],"footnotes":[],"attachments":[]},"openArchive":false,"openAccess":false,"document-subtype":"fla","content-family":"serial","contentType":"JL","entitlementType":"","pdf":{"urlType":null},"iss-first":"","vol-first":"101","isThirdParty":false,"language":"en","issn-primary-unformatted":"13618415","issn-primary-formatted":"1361-8415"},{"pii":"S1361841524003578","doi":"10.1016/j.media.2024.103432","journalTitle":"Medical Image Analysis","publicationYear":"2025","publicationDate":"2025-04-01","volumeSupText":"Volume 101","articleNumber":"103432","pageRange":"103432","trace-token":"AAAAQGXIqwOoU49vlm_PnlcrBlrF2Vt8aUIqRj5rqSf7GljKN3W4tMIkwOQvIsxc4lkGo6dffYuX9yZ7aYJzbGjw8j_Y6nGkS2Bls7v9NPric0Ncw4PPow","authors":{"content":[{"#name":"author-group","$":{"id":"d1e1540"},"$$":[{"#name":"author","$":{"author-id":"S1361841524003578-61bf7beef624606283c14b2b85e9bbfe","id":"au000001","orcid":"0000-0003-1187-2835"},"$$":[{"#name":"given-name","_":"Chunming"},{"#name":"surname","_":"Li"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"cross-ref","$":{"id":"d1e1552","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-41394d730d37207251c503024bd3bfb7","id":"au000002"},"$$":[{"#name":"given-name","_":"Yuchuan"},{"#name":"surname","_":"Qiao"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e1562","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-b1c3b91406d72b5b8023dfb45dd4260b","id":"au000003","orcid":"0000-0002-3135-0148"},"$$":[{"#name":"given-name","_":"Wei"},{"#name":"surname","_":"Yu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1574","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-d8b171a6f9e556b5830ce43cb719abf3","id":"au000004","orcid":"0000-0003-3907-4309"},"$$":[{"#name":"given-name","_":"Yingguang"},{"#name":"surname","_":"Li"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1586","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-45c722321377d2f9146d5c0aea34413e","id":"au000005"},"$$":[{"#name":"given-name","_":"Yankai"},{"#name":"surname","_":"Chen"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1598","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-edc52b3e6465e2a5a4fb44da2698af23","id":"au000006"},"$$":[{"#name":"given-name","_":"Zehao"},{"#name":"surname","_":"Fan"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1608","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-84011a81b86025e6e43ed9df9ce3ff23","id":"au000007"},"$$":[{"#name":"given-name","_":"Runguo"},{"#name":"surname","_":"Wei"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1618","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-0748f06d362b91fa890b97eea3546ebb","id":"au000008"},"$$":[{"#name":"given-name","_":"Botao"},{"#name":"surname","_":"Yang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"cross-ref","$":{"id":"d1e1628","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-f7ef40a3032bba19dfd348cc5d548f15","id":"au000009"},"$$":[{"#name":"given-name","_":"Zhiqing"},{"#name":"surname","_":"Wang"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"cross-ref","$":{"id":"d1e1638","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-4f58d51d6f0c8b0a90cec0259b68f940","id":"au000010"},"$$":[{"#name":"given-name","_":"Xuesong"},{"#name":"surname","_":"Lu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e1648","refid":"aff5"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"e"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-2d842f60d1cdaf709418a50d59c905ca","id":"au000011"},"$$":[{"#name":"given-name","_":"Lianglong"},{"#name":"surname","_":"Chen"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"cross-ref","$":{"id":"d1e1658","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-501117973d6ec71db303971e3bf565a2","id":"au000012"},"$$":[{"#name":"given-name","_":"Carlos"},{"#name":"surname","_":"Collet"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"cross-ref","$":{"id":"d1e1669","refid":"aff6"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"f"}]}]},{"#name":"author","$":{"author-id":"S1361841524003578-8228953cd7936bcc81fd648b5eb36eb0","id":"au000013"},"$$":[{"#name":"given-name","_":"Miao"},{"#name":"surname","_":"Chu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"cross-ref","$":{"id":"d1e1683","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1686","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]},{"#name":"cross-ref","$":{"id":"d1e1689","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea1","type":"email","href":"mailto:chumiao@sjtu.edu.cn"},"_":"chumiao@sjtu.edu.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003578-08d9ed545b4d890a7fdbf8930566d11c","id":"au000014","orcid":"0000-0001-9681-1067"},"$$":[{"#name":"given-name","_":"Shengxian"},{"#name":"surname","_":"Tu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1707","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1710","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]},{"#name":"cross-ref","$":{"id":"d1e1713","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:sxtu@sjtu.edu.cn"},"_":"sxtu@sjtu.edu.cn"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-460ca7553d43c08dc3b6bae2b5953422","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"School of Biomedical Engineering, Shanghai Jiao Tong University, Shanghai 200030, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biomedical Engineering, Shanghai Jiao Tong University"},{"#name":"city","_":"Shanghai"},{"#name":"postal-code","_":"200030"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs53"},"_":"School of Biomedical Engineering, Shanghai Jiao Tong University, Shanghai 200030, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-3b764dbd3f166c42853fee0dbc1e84e4","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"Institute of Science and Technology for Brain-Inspired Intelligence, Fudan University, Shanghai 201200, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Institute of Science and Technology for Brain-Inspired Intelligence, Fudan University"},{"#name":"city","_":"Shanghai"},{"#name":"postal-code","_":"201200"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs54"},"_":"Institute of Science and Technology for Brain-Inspired Intelligence, Fudan University, Shanghai 201200, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-37c4921a7490c7df860cfbef482b7f48","id":"aff3"},"$$":[{"#name":"label","_":"c"},{"#name":"textfn","_":"International Smart Medical Devices Innovation Center, Kunshan Industrial Technology Research Institute, Suzhou, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"International Smart Medical Devices Innovation Center, Kunshan Industrial Technology Research Institute"},{"#name":"city","_":"Suzhou"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs55"},"_":"International Smart Medical Devices Innovation Center, Kunshan Industrial Technology Research Institute, Suzhou, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-c3f2f1e0d045060d8e002997db4a9534","id":"aff4"},"$$":[{"#name":"label","_":"d"},{"#name":"textfn","_":"Department of Cardiology, Fujian Medical University Union Hospital, Fuzhou, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Cardiology, Fujian Medical University Union Hospital"},{"#name":"city","_":"Fuzhou"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs56"},"_":"Department of Cardiology, Fujian Medical University Union Hospital, Fuzhou, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-e52d5824e15a067c5e8355a21035fed5","id":"aff5"},"$$":[{"#name":"label","_":"e"},{"#name":"textfn","_":"School of Biomedical Engineering, South-Central Minzu University, Wuhan 430074, Hubei, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biomedical Engineering, South-Central Minzu University"},{"#name":"city","_":"Wuhan"},{"#name":"state","_":"Hubei"},{"#name":"postal-code","_":"430074"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs57"},"_":"School of Biomedical Engineering, South-Central Minzu University, Wuhan 430074, Hubei, China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-1bf1a5d6d2b98155c48b4b69b895f06c","id":"aff6"},"$$":[{"#name":"label","_":"f"},{"#name":"textfn","_":"Cardiovascular Center Aalst, OLV Clinic, Aalst, Belgium"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Cardiovascular Center Aalst, OLV Clinic"},{"#name":"city","_":"Aalst"},{"#name":"country","$":{"iso3166-1-alpha-3":"BEL"},"_":"Belgium"}]},{"#name":"source-text","$":{"id":"afs58"},"_":"Cardiovascular Center Aalst, OLV Clinic, Aalst, Belgium"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003578-5c82482cb37918d15a898c287523a193","id":"aff7"},"$$":[{"#name":"label","_":"g"},{"#name":"textfn","_":"Department of Cardiovascular Medicine, University of Oxford, OX39DU, UK"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Cardiovascular Medicine, University of Oxford"},{"#name":"postal-code","_":"OX39DU"},{"#name":"country","$":{"iso3166-1-alpha-3":"GBR"},"_":"UK"}]},{"#name":"source-text","$":{"id":"afs59"},"_":"Department of Cardiovascular Medicine, University of Oxford, OX39DU, UK"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding authors at: School of Biomedical Engineering, Shanghai Jiao Tong University, Shanghai 200030, China."},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biomedical Engineering, Shanghai Jiao Tong University"},{"#name":"city","_":"Shanghai"},{"#name":"postal-code","_":"200030"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]}]}]}],"floats":[],"footnotes":[],"attachments":[]},"lastAuthor":{"content":[{"#name":"author","$":{"author-id":"S1361841524003578-08d9ed545b4d890a7fdbf8930566d11c","id":"au000014","orcid":"0000-0001-9681-1067"},"$$":[{"#name":"given-name","_":"Shengxian"},{"#name":"surname","_":"Tu"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e1707","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e1710","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]},{"#name":"cross-ref","$":{"id":"d1e1713","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea2","type":"email","href":"mailto:sxtu@sjtu.edu.cn"},"_":"sxtu@sjtu.edu.cn"}]}],"floats":[],"footnotes":[],"attachments":[]},"title":{"content":[{"#name":"title","$":{"id":"d1e1537"},"_":"AutoFOX: An automated cross-modal 3D fusion framework of coronary X-ray angiography and OCT"}],"floats":[],"footnotes":[],"attachments":[]},"openArchive":false,"openAccess":false,"document-subtype":"fla","content-family":"serial","contentType":"JL","entitlementType":"","pdf":{"urlType":null},"iss-first":"","vol-first":"101","isThirdParty":false,"language":"en","issn-primary-unformatted":"13618415","issn-primary-formatted":"1361-8415"},{"pii":"S1361841524003645","doi":"10.1016/j.media.2024.103439","journalTitle":"Medical Image Analysis","publicationYear":"2025","publicationDate":"2025-04-01","volumeSupText":"Volume 101","articleNumber":"103439","pageRange":"103439","trace-token":"AAAAQGXIqwOoU49vlm_PnlcrBlrF2Vt8aUIqRj5rqSf7GljK8E1th-FuKv0NRbSKCWLSHIR5P1gzkGotNRJMk7InqaKaFq0K0vZ35FjhJursdQdbb3tUaA","authors":{"content":[{"#name":"author-group","$":{"id":"d1e912"},"$$":[{"#name":"author","$":{"author-id":"S1361841524003645-0a94c3a94014fbf03cf7ddc5db078081","id":"au000001","orcid":"0000-0003-1943-0548"},"$$":[{"#name":"given-name","_":"Golriz"},{"#name":"surname","_":"Hosseinimanesh"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-original-draft"},"_":"Writing – original draft"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/visualization"},"_":"Visualization"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/software"},"_":"Software"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/investigation"},"_":"Investigation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/formal-analysis"},"_":"Formal analysis"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/data-curation"},"_":"Data curation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e937","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e940","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea1","type":"email","href":"mailto:golriz.hosseinimanesh@polymtl.ca"},"_":"golriz.hosseinimanesh@polymtl.ca"}]},{"#name":"author","$":{"author-id":"S1361841524003645-1962944b817c9807f67f19e7fd575d45","id":"au000002","orcid":"0000-0001-5651-7103"},"$$":[{"#name":"given-name","_":"Ammar"},{"#name":"surname","_":"Alsheghri"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/validation"},"_":"Validation"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"cross-ref","$":{"id":"d1e954","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]},{"#name":"cross-ref","$":{"id":"d1e957","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]}]},{"#name":"author","$":{"author-id":"S1361841524003645-f71eb0b50f305a1d0b58effa1a2aecaa","id":"au000003"},"$$":[{"#name":"given-name","_":"Julia"},{"#name":"surname","_":"Keren"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"cross-ref","$":{"id":"d1e967","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]}]},{"#name":"author","$":{"author-id":"S1361841524003645-8976f0070230818293d050dd02072444","id":"au000004"},"$$":[{"#name":"given-name","_":"Farida"},{"#name":"surname","_":"Cheriet"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"cross-ref","$":{"id":"d1e979","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"author","$":{"author-id":"S1361841524003645-dba9497f5435c9ea59b22326610e8d65","id":"au000005","orcid":"0000-0002-3934-4631"},"$$":[{"#name":"given-name","_":"Francois"},{"#name":"surname","_":"Guibault"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"cross-ref","$":{"id":"d1e993","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003645-45a9e9e9bd8efbd20eba057d43442e47","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"Polytechnique Montréal University, Canada"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Polytechnique Montréal University"},{"#name":"country","$":{"iso3166-1-alpha-3":"CAN"},"_":"Canada"}]},{"#name":"source-text","$":{"id":"afs50"},"_":"Polytechnique Montréal University, Canada"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003645-33db5dfd962e9b350b18b7bea74711fa","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"Mechanical Engineering Department, King Fahd University of Petroleum and Minerals (KFUPM), Dhahran, 31261, Kingdom of Saudi Arabia"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Mechanical Engineering Department, King Fahd University of Petroleum and Minerals (KFUPM)"},{"#name":"city","_":"Dhahran"},{"#name":"postal-code","_":"31261"},{"#name":"country","$":{"iso3166-1-alpha-3":"SAU"},"_":"Kingdom of Saudi Arabia"}]},{"#name":"source-text","$":{"id":"afs51"},"_":"Mechanical Engineering Department, King Fahd University of Petroleum and Minerals (KFUPM), Dhahran, 31261, KSA"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003645-fee49670f013034422f41276bd91b9b5","id":"aff3"},"$$":[{"#name":"label","_":"c"},{"#name":"textfn","_":"Interdisciplinary research center for Biosystems and Machines, King Fahd University of Petroleum and Minerals (KFUPM), Dhahran, Kingdom of Saudi Arabia"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Interdisciplinary research center for Biosystems and Machines, King Fahd University of Petroleum and Minerals (KFUPM)"},{"#name":"city","_":"Dhahran"},{"#name":"country","$":{"iso3166-1-alpha-3":"SAU"},"_":"Kingdom of Saudi Arabia"}]},{"#name":"source-text","$":{"id":"afs52"},"_":"Interdisciplinary research center for Biosystems and Machines, King Fahd University of Petroleum and Minerals (KFUPM), Dhahran, KSA"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003645-0a0f749d3a51ca64c2676749580419de","id":"aff4"},"$$":[{"#name":"label","_":"d"},{"#name":"textfn","_":"Intellident Dentaire Inc., Canada"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Intellident Dentaire Inc."},{"#name":"country","$":{"iso3166-1-alpha-3":"CAN"},"_":"Canada"}]},{"#name":"source-text","$":{"id":"afs53"},"_":"Intellident Dentaire Inc., Canada"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding author."}]}]}],"floats":[],"footnotes":[],"attachments":[]},"lastAuthor":{"content":[{"#name":"author","$":{"author-id":"S1361841524003645-dba9497f5435c9ea59b22326610e8d65","id":"au000005","orcid":"0000-0002-3934-4631"},"$$":[{"#name":"given-name","_":"Francois"},{"#name":"surname","_":"Guibault"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/supervision"},"_":"Supervision"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/funding-acquisition"},"_":"Funding acquisition"},{"#name":"cross-ref","$":{"id":"d1e993","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]}]}],"floats":[],"footnotes":[],"attachments":[]},"title":{"content":[{"#name":"title","$":{"id":"d1e909"},"_":"Personalized dental crown design: A point-to-mesh completion network"}],"floats":[],"footnotes":[],"attachments":[]},"openArchive":false,"openAccess":true,"document-subtype":"fla","content-family":"serial","contentType":"JL","entitlementType":"","pdf":{"urlType":null},"iss-first":"","vol-first":"101","isThirdParty":false,"language":"en","issn-primary-unformatted":"13618415","issn-primary-formatted":"1361-8415"},{"pii":"S1361841524003098","doi":"10.1016/j.media.2024.103384","journalTitle":"Medical Image Analysis","publicationYear":"2025","publicationDate":"2025-02-01","volumeSupText":"Volume 100","articleNumber":"103384","pageRange":"103384","trace-token":"AAAAQGXIqwOoU49vlm_PnlcrBlrF2Vt8aUIqRj5rqSf7GljKJmfHLtiqsecE0H2Euq3ZYc6IPCLsFXDnOaUzRxZESwUyNP2PSE9FVsBj2WoHRFbUHrSOKg","authors":{"content":[{"#name":"author-group","$":{"id":"d1e2669"},"$$":[{"#name":"author","$":{"author-id":"S1361841524003098-d8d01f9e12e92a2e691b311c1a3dfd48","id":"au000001"},"$$":[{"#name":"given-name","_":"Kai-Ni"},{"#name":"surname","_":"Wang"},{"#name":"cross-ref","$":{"id":"d1e2675","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e2678","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]}]},{"#name":"author","$":{"author-id":"S1361841524003098-b87ddc3d017e19b6b641b81184d53904","id":"au000002"},"$$":[{"#name":"given-name","_":"Haolin"},{"#name":"surname","_":"Wang"},{"#name":"cross-ref","$":{"id":"d1e2686","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e2689","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]}]},{"#name":"author","$":{"author-id":"S1361841524003098-1b73bdce71e74ed1b016ba5100b585be","id":"au000003"},"$$":[{"#name":"given-name","_":"Guang-Quan"},{"#name":"surname","_":"Zhou"},{"#name":"cross-ref","$":{"id":"d1e2697","refid":"aff1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"a"}]},{"#name":"cross-ref","$":{"id":"d1e2700","refid":"aff2"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"b"}]},{"#name":"cross-ref","$":{"id":"d1e2703","refid":"cor1"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"⁎"}]},{"#name":"e-address","$":{"xmlns:xlink":true,"id":"ea1","type":"email","href":"mailto:guangquan.zhou@seu.edu.cn"},"_":"guangquan.zhou@seu.edu.cn"}]},{"#name":"author","$":{"author-id":"S1361841524003098-85184fed61386daf34db9e45b8fffb66","id":"au000004"},"$$":[{"#name":"given-name","_":"Yangang"},{"#name":"surname","_":"Wang"},{"#name":"cross-ref","$":{"id":"d1e2713","refid":"aff5"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"e"}]}]},{"#name":"author","$":{"author-id":"S1361841524003098-730128334270c1fecba594f9c4a76f14","id":"au000005"},"$$":[{"#name":"given-name","_":"Ling"},{"#name":"surname","_":"Yang"},{"#name":"cross-ref","$":{"id":"d1e2721","refid":"aff6"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"f"}]}]},{"#name":"author","$":{"author-id":"S1361841524003098-7eabe8d913d89c7a8774ac0a3ad08ca0","id":"au000006"},"$$":[{"#name":"given-name","_":"Yang"},{"#name":"surname","_":"Chen"},{"#name":"cross-ref","$":{"id":"d1e2729","refid":"aff3"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"c"}]},{"#name":"cross-ref","$":{"id":"d1e2732","refid":"aff4"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"d"}]}]},{"#name":"author","$":{"author-id":"S1361841524003098-2e64875acb02d3a231ad4e3b69aaea82","id":"au000007","orcid":"0000-0002-5184-3230"},"$$":[{"#name":"given-name","_":"Shuo"},{"#name":"surname","_":"Li"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e2746","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-579a8068c0b97baedc6c5a6f04cfacaf","id":"aff1"},"$$":[{"#name":"label","_":"a"},{"#name":"textfn","_":"School of Biological Science and Medical Engineering, Southeast University, Nanjing, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"School of Biological Science and Medical Engineering, Southeast University"},{"#name":"city","_":"Nanjing"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs59"},"_":"o=School of Biological Science and Medical Engineering, Southeast University, c=Nanjing, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-248f5d573d9e98723b0d9252a3801295","id":"aff2"},"$$":[{"#name":"label","_":"b"},{"#name":"textfn","_":"Jiangsu Key Laboratory of Biomaterials and Devices, Southeast University, Nanjing, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Jiangsu Key Laboratory of Biomaterials and Devices, Southeast University"},{"#name":"city","_":"Nanjing"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs60"},"_":"o=Jiangsu Key Laboratory of Biomaterials and Devices, Southeast University, c=Nanjing, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-c847860dc014d755a98e766dc0ac9162","id":"aff3"},"$$":[{"#name":"label","_":"c"},{"#name":"textfn","_":"Laboratory of Image Science and Technology, Southeast University, Nanjing, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Laboratory of Image Science and Technology, Southeast University"},{"#name":"city","_":"Nanjing"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs61"},"_":"o=Laboratory of Image Science and Technology, Southeast University, c=Nanjing, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-fbabfb6c78d1406b3f8c45e8735fe73a","id":"aff4"},"$$":[{"#name":"label","_":"d"},{"#name":"textfn","_":"Key Laboratory of Computer Network and Information Integration, Southeast University, Nanjing, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Key Laboratory of Computer Network and Information Integration, Southeast University"},{"#name":"city","_":"Nanjing"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs62"},"_":"o=Key Laboratory of Computer Network and Information Integration, Southeast University, c=Nanjing, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-b5475018153b82448bf47ff2802cc9f8","id":"aff5"},"$$":[{"#name":"label","_":"e"},{"#name":"textfn","_":"TUGE Healthcare, Nanjing, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"TUGE Healthcare"},{"#name":"city","_":"Nanjing"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs63"},"_":"o=TUGE Healthcare, c=Nanjing, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-86a3e0e42d54ff656636df8b12774195","id":"aff6"},"$$":[{"#name":"label","_":"f"},{"#name":"textfn","_":"Institute of Medical Technology, Peking University Health Science Center, China"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Institute of Medical Technology, Peking University Health Science Center"},{"#name":"country","$":{"iso3166-1-alpha-3":"CHN"},"_":"China"}]},{"#name":"source-text","$":{"id":"afs64"},"_":"o=Institute of Medical Technology, Peking University Health Science Center, cy=China"}]},{"#name":"affiliation","$":{"affiliation-id":"S1361841524003098-15bfaba1583c95f5ed1753e3ae0bb655","id":"aff7"},"$$":[{"#name":"label","_":"g"},{"#name":"textfn","_":"Department of Computer and Data Science and Department of Biomedical Engineering, Case Western Reserve University, USA"},{"#name":"affiliation","$":{"xmlns:sa":true},"$$":[{"#name":"organization","_":"Department of Computer and Data Science and Department of Biomedical Engineering, Case Western Reserve University"},{"#name":"country","$":{"iso3166-1-alpha-3":"USA"},"_":"USA"}]},{"#name":"source-text","$":{"id":"afs65"},"_":"o=Department of Computer and Data Science and Department of Biomedical Engineering, Case Western Reserve University, cy=USA"}]},{"#name":"correspondence","$":{"id":"cor1"},"$$":[{"#name":"label","_":"⁎"},{"#name":"text","_":"Corresponding author."}]}]}],"floats":[],"footnotes":[],"attachments":[]},"lastAuthor":{"content":[{"#name":"author","$":{"author-id":"S1361841524003098-2e64875acb02d3a231ad4e3b69aaea82","id":"au000007","orcid":"0000-0002-5184-3230"},"$$":[{"#name":"given-name","_":"Shuo"},{"#name":"surname","_":"Li"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/writing-review-editing"},"_":"Writing – review & editing"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/methodology"},"_":"Methodology"},{"#name":"contributor-role","$":{"role":"http://credit.niso.org/contributor-roles/conceptualization"},"_":"Conceptualization"},{"#name":"cross-ref","$":{"id":"d1e2746","refid":"aff7"},"$$":[{"#name":"sup","$":{"loc":"post"},"_":"g"}]}]}],"floats":[],"footnotes":[],"attachments":[]},"title":{"content":[{"#name":"title","$":{"id":"d1e2666"},"_":"TSdetector: Temporal–Spatial self-correction collaborative learning for colonoscopy video detection"}],"floats":[],"footnotes":[],"attachments":[]},"openArchive":false,"openAccess":false,"document-subtype":"fla","content-family":"serial","contentType":"JL","entitlementType":"","pdf":{"urlType":null},"iss-first":"","vol-first":"100","isThirdParty":false,"language":"en","issn-primary-unformatted":"13618415","issn-primary-formatted":"1361-8415"}]},"references":{"content":[{"#name":"bibliography","$":{"xmlns:ce":true,"xmlns:aep":true,"xmlns:mml":true,"xmlns:xs":true,"xmlns:xlink":true,"xmlns:xocs":true,"xmlns:tb":true,"xmlns:xsi":true,"xmlns:cals":true,"xmlns:sb":true,"xmlns:sa":true,"xmlns:ja":true,"xmlns":true,"id":"bib1","view":"all"},"$$":[{"#name":"section-title","$":{"id":"d1e16214"},"_":"References"},{"#name":"bibliography-sec","$":{"id":"d1e16216","view":"all"},"$$":[{"#name":"bib-reference","$":{"id":"b1"},"$$":[{"#name":"label","_":"Amemiya et al., 2016"},{"#name":"reference","$":{"id":"sb1","refId":"1"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Amemiya"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Takao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Hanaoka"}]},{"#name":"author","$$":[{"#name":"given-name","_":"K."},{"#name":"surname","_":"Ohtomo"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Global and structured waves of rs-fMRI signal identified as putative propagation of spontaneous neural activity"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Neuroimage"}]},{"#name":"volume-nr","_":"133"}]},{"#name":"date","_":"2016"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"331"},{"#name":"last-page","_":"340"}]}]}]},{"#name":"source-text","$":{"id":"afs1"},"_":"Amemiya, S., Takao, H., Hanaoka, S., Ohtomo, K., 2016. Global and structured waves of rs-fMRI signal identified as putative propagation of spontaneous neural activity. NeuroImage 133, 331–340."}]},{"#name":"bib-reference","$":{"id":"b2"},"$$":[{"#name":"label","_":"Bessadok et al., 2022"},{"#name":"reference","$":{"id":"sb2","refId":"2"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Bessadok"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M.A."},{"#name":"surname","_":"Mahjoub"}]},{"#name":"author","$$":[{"#name":"given-name","_":"I."},{"#name":"surname","_":"Rekik"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Graph neural networks in network neuroscience"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Pattern Anal. Mach. Intell."}]},{"#name":"volume-nr","_":"45"}]},{"#name":"issue-nr","_":"5"},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"5833"},{"#name":"last-page","_":"5848"}]}]}]},{"#name":"source-text","$":{"id":"afs2"},"_":"Bessadok, A., Mahjoub, M.A., Rekik, I., 2022. Graph neural networks in network neuroscience. IEEE Transactions on Pattern Analysis and Machine Intelligence 45, 5833–5848."}]},{"#name":"bib-reference","$":{"id":"b3"},"$$":[{"#name":"label","_":"Bijsterbosch et al., 2017"},{"#name":"reference","$":{"id":"sb3","refId":"3"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Bijsterbosch"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S.M."},{"#name":"surname","_":"Smith"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Beckmann"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"An Introduction to Resting State fMRI Functional Connectivity"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2017"},{"#name":"publisher","$$":[{"#name":"name","_":"Oxford University Press"}]}]}]}]},{"#name":"source-text","$":{"id":"afs3"},"_":"Bijsterbosch, J., Smith, S.M., Beckmann, C., 2017. An introduction to resting state fMRI functional connectivity. Oxford University Press."}]},{"#name":"bib-reference","$":{"id":"b4"},"$$":[{"#name":"label","_":"Bondi et al., 2023"},{"#name":"reference","$":{"id":"sb4","refId":"4"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Bondi"}]},{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Maggioni"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Brambilla"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Delvecchio"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A systematic review on the potential use of machine learning to classify major depressive disorder from healthy controls using resting state fMRI measures"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Neurosci. Biobehav. Rev."}]},{"#name":"volume-nr","_":"144"}]},{"#name":"date","_":"2023"}]},{"#name":"article-number","_":"104972"}]}]},{"#name":"source-text","$":{"id":"afs4"},"_":"Bondi, E., Maggioni, E., Brambilla, P., Delvecchio, G., 2023. A systematic review on the potential use of machine learning to classify major depressive disorder from healthy controls using resting state fMRI measures. Neuroscience & Biobehavioral Reviews 144, 104972."}]},{"#name":"bib-reference","$":{"id":"b5"},"$$":[{"#name":"label","_":"Chen and He, 2021"},{"#name":"other-ref","$":{"id":"sb5","refId":"5"},"$$":[{"#name":"textref","_":"Chen, X., He, K., 2021. Exploring simple Siamese representation learning. In: Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. pp. 15750–15758."}]}]},{"#name":"bib-reference","$":{"id":"b6"},"$$":[{"#name":"label","_":"Chen et al., 2020"},{"#name":"reference","$":{"id":"sb6","refId":"6"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Chen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Kornblith"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Norouzi"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Hinton"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A simple framework for contrastive learning of visual representations"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"International Conference on Machine Learning"}]},{"#name":"date","_":"2020"},{"#name":"publisher","$$":[{"#name":"name","_":"PMLR"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1597"},{"#name":"last-page","_":"1607"}]}]}]},{"#name":"source-text","$":{"id":"afs5"},"_":"Chen, T., Kornblith, S., Norouzi, M., Hinton, G., 2020. A simple framework for contrastive learning of visual representations, in: International Conference on Machine Learning, PMLR. pp. 1597–1607."}]},{"#name":"bib-reference","$":{"id":"b7"},"$$":[{"#name":"label","_":"Cui et al., 2023"},{"#name":"reference","$":{"id":"sb7","refId":"7"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Cui"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Du"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Sun"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Zhu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Zhao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Peng"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Tan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Li"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Dynamic multi-site graph convolutional network for autism spectrum disorder identification"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Comput. Biol. Med."}]},{"#name":"volume-nr","_":"157"}]},{"#name":"date","_":"2023"}]},{"#name":"article-number","_":"106749"}]}]},{"#name":"source-text","$":{"id":"afs7"},"_":"Cui, W., Du, J., Sun, M., Zhu, S., Zhao, S., Peng, Z., Tan, L., Li, Y., 2023. Dynamic multi-site graph convolutional network for autism spectrum disorder identification. Computers in Biology and Medicine 157, 106749."}]},{"#name":"bib-reference","$":{"id":"b8"},"$$":[{"#name":"label","_":"Dai et al., 2023"},{"#name":"reference","$":{"id":"sb8","refId":"8"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Dai"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Lu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Shi"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Zhou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Xiong"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Zhou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Chen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Zou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Tang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Huang"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Classification of recurrent major depressive disorder using a new time series feature extraction method through multisite rs-fMRI data"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"J. Affect. Disord."}]},{"#name":"volume-nr","_":"339"}]},{"#name":"date","_":"2023"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"511"},{"#name":"last-page","_":"519"}]}]}]},{"#name":"source-text","$":{"id":"afs8"},"_":"Dai, P., Lu, D., Shi, Y., Zhou, Y., Xiong, T., Zhou, X., Chen, Z., Zou, B., Tang, H., Huang, Z., et al., 2023. Classification of recurrent major depressive disorder using a new time series feature extraction method through multisite rs-fMRI data. Journal of Affective Disorders 339, 511–519."}]},{"#name":"bib-reference","$":{"id":"b9"},"$$":[{"#name":"label","_":"Demirel and Holz, 2024"},{"#name":"reference","$":{"id":"sb9","refId":"9"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"B.U."},{"#name":"surname","_":"Demirel"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Holz"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Finding order in chaos: A novel data augmentation method for time series in contrastive learning"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"36"}]},{"#name":"date","_":"2024"}]}]}]},{"#name":"source-text","$":{"id":"afs9"},"_":"Demirel, B.U., Holz, C., 2024. Finding order in chaos: A novel data augmentation method for time series in contrastive learning. Advances in Neural Information Processing Systems 36."}]},{"#name":"bib-reference","$":{"id":"b10"},"$$":[{"#name":"label","_":"Dwivedi and Bresson, 2020"},{"#name":"reference","$":{"id":"sb10","refId":"10"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"V.P."},{"#name":"surname","_":"Dwivedi"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Bresson"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A generalization of transformer networks to graphs"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2020"}]}]},{"#name":"comment","$$":[{"#name":"__text__","_":"arXiv preprint "},{"#name":"inter-ref","$":{"id":"interref9","href":"arxiv:2012.09699","role":"http://www.elsevier.com/xml/linking-roles/preprint","type":"simple"},"_":"arXiv:2012.09699"}]}]},{"#name":"source-text","$":{"id":"afs10"},"_":"Dwivedi, V.P., Bresson, X., 2020. A generalization of Transformer networks to graphs. arXiv preprint arXiv:2012.09699 ."}]},{"#name":"bib-reference","$":{"id":"b11"},"$$":[{"#name":"label","_":"Ecker et al., 2015"},{"#name":"reference","$":{"id":"sb11","refId":"11"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Ecker"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S.Y."},{"#name":"surname","_":"Bookheimer"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.G."},{"#name":"surname","_":"Murphy"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Neuroimaging in autism spectrum disorder: Brain structure and function across the lifespan"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Lancet Neurol."}]},{"#name":"volume-nr","_":"14"}]},{"#name":"issue-nr","_":"11"},{"#name":"date","_":"2015"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1121"},{"#name":"last-page","_":"1134"}]}]}]},{"#name":"source-text","$":{"id":"afs11"},"_":"Ecker, C., Bookheimer, S.Y., Murphy, D.G., 2015. Neuroimaging in autism spectrum disorder: Brain structure and function across the lifespan. The Lancet Neurology 14, 1121–1134."}]},{"#name":"bib-reference","$":{"id":"b12"},"$$":[{"#name":"label","_":"Ericsson et al., 2022"},{"#name":"reference","$":{"id":"sb12","refId":"12"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Ericsson"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Gouk"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C.C."},{"#name":"surname","_":"Loy"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T.M."},{"#name":"surname","_":"Hospedales"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Self-supervised representation learning: Introduction, advances, and challenges"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Signal Process. Mag."}]},{"#name":"volume-nr","_":"39"}]},{"#name":"issue-nr","_":"3"},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"42"},{"#name":"last-page","_":"62"}]}]}]},{"#name":"source-text","$":{"id":"afs12"},"_":"Ericsson, L., Gouk, H., Loy, C.C., Hospedales, T.M., 2022. Self-supervised representation learning: Introduction, advances, and challenges. IEEE Signal Processing Magazine 39, 42–62."}]},{"#name":"bib-reference","$":{"id":"b13"},"$$":[{"#name":"label","_":"Fang et al., 2023"},{"#name":"reference","$":{"id":"sb13","refId":"13"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Fang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G.G."},{"#name":"surname","_":"Potter"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Liu"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Unsupervised cross-domain functional MRI adaptation for automated major depressive disorder identification"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Med. Image Anal."}]},{"#name":"volume-nr","_":"84"}]},{"#name":"date","_":"2023"}]},{"#name":"article-number","_":"102707"}]}]},{"#name":"source-text","$":{"id":"afs13"},"_":"Fang, Y., Wang, M., Potter, G.G., Liu, M., 2023. Unsupervised cross-domain functional MRI adaptation for automated major depressive disorder identification. Medical Image Analysis 84, 102707."}]},{"#name":"bib-reference","$":{"id":"b14"},"$$":[{"#name":"label","_":"Fedorov et al., 2024"},{"#name":"reference","$":{"id":"sb14","refId":"14"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Fedorov"}]},{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Geenjaar"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Wu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Sylvain"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T.P."},{"#name":"surname","_":"DeRamus"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Luck"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Misiura"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Mittapalle"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R.D."},{"#name":"surname","_":"Hjelm"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S.M."},{"#name":"surname","_":"Plis"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Self-supervised multimodal learning for group inferences from MRI data: Discovering disorder-relevant brain regions and multimodal links"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Neuroimage"}]},{"#name":"volume-nr","_":"285"}]},{"#name":"date","_":"2024"}]},{"#name":"article-number","_":"120485"}]}]},{"#name":"source-text","$":{"id":"afs14"},"_":"Fedorov, A., Geenjaar, E., Wu, L., Sylvain, T., DeRamus, T.P., Luck, M., Misiura, M., Mittapalle, G., Hjelm, R.D., Plis, S.M., et al., 2024. Self-supervised multimodal learning for group inferences from MRI data: Discovering disorder-relevant brain regions and multimodal links. NeuroImage 285, 120485."}]},{"#name":"bib-reference","$":{"id":"b15"},"$$":[{"#name":"label","_":"Guan and Liu, 2021"},{"#name":"reference","$":{"id":"sb15","refId":"15"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Guan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Liu"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Domain adaptation for medical image analysis: A survey"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Biomed. Eng."}]},{"#name":"volume-nr","_":"69"}]},{"#name":"issue-nr","_":"3"},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1173"},{"#name":"last-page","_":"1185"}]}]}]},{"#name":"source-text","$":{"id":"afs15"},"_":"Guan, H., Liu, M., 2021. Domain adaptation for medical image analysis: A survey. IEEE Transactions on Biomedical Engineering 69, 1173–1185."}]},{"#name":"bib-reference","$":{"id":"b16"},"$$":[{"#name":"label","_":"Guo and Zhao, 2022"},{"#name":"reference","$":{"id":"sb16","refId":"16"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Guo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Zhao"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A systematic survey on deep generative models for graph generation"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Pattern Anal. Mach. Intell."}]},{"#name":"volume-nr","_":"45"}]},{"#name":"issue-nr","_":"5"},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"5370"},{"#name":"last-page","_":"5390"}]}]}]},{"#name":"source-text","$":{"id":"afs16"},"_":"Guo, X., Zhao, L., 2022. A systematic survey on deep generative models for graph generation. IEEE Transactions on Pattern Analysis and Machine Intelligence 45, 5370–5390."}]},{"#name":"bib-reference","$":{"id":"b17"},"$$":[{"#name":"label","_":"He et al., 2020"},{"#name":"other-ref","$":{"id":"sb17","refId":"17"},"$$":[{"#name":"textref","_":"He, K., Fan, H., Wu, Y., Xie, S., Girshick, R., 2020. Momentum contrast for unsupervised visual representation learning. In: Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. pp. 9729–9738."}]}]},{"#name":"bib-reference","$":{"id":"b18"},"$$":[{"#name":"label","_":"Hebling Vieira et al., 2021"},{"#name":"reference","$":{"id":"sb18","refId":"18"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Hebling Vieira"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Dubois"}]},{"#name":"author","$$":[{"#name":"given-name","_":"V.D."},{"#name":"surname","_":"Calhoun"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C.E."},{"#name":"surname","_":"Garrido Salmon"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A deep learning based approach identifies regions more relevant than resting-state networks to the prediction of general intelligence from resting-state fMRI"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Hum. Brain Mapp."}]},{"#name":"volume-nr","_":"42"}]},{"#name":"issue-nr","_":"18"},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"5873"},{"#name":"last-page","_":"5887"}]}]}]},{"#name":"source-text","$":{"id":"afs18"},"_":"Hebling Vieira, B., Dubois, J., Calhoun, V.D., Garrido Salmon, C.E., 2021. A deep learning based approach identifies regions more relevant than resting-state networks to the prediction of general intelligence from resting-state fMRI. Human Brain Mapping 42, 5873–5887."}]},{"#name":"bib-reference","$":{"id":"b19"},"$$":[{"#name":"label","_":"Hendrycks et al., 2019"},{"#name":"reference","$":{"id":"sb19","refId":"19"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Hendrycks"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Mazeika"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Kadavath"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Song"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Using self-supervised learning can improve model robustness and uncertainty"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"32"}]},{"#name":"date","_":"2019"}]}]}]},{"#name":"source-text","$":{"id":"afs19"},"_":"Hendrycks, D., Mazeika, M., Kadavath, S., Song, D., 2019. Using self-supervised learning can improve model robustness and uncertainty. Advances in Neural Information Processing Systems 32."}]},{"#name":"bib-reference","$":{"id":"b20"},"$$":[{"#name":"label","_":"Ho et al., 2020"},{"#name":"reference","$":{"id":"sb20","refId":"20"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Ho"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Jain"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Abbeel"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Denoising diffusion probabilistic models"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"33"}]},{"#name":"date","_":"2020"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"6840"},{"#name":"last-page","_":"6851"}]}]}]},{"#name":"source-text","$":{"id":"afs20"},"_":"Ho, J., Jain, A., Abbeel, P., 2020. Denoising diffusion probabilistic models. Advances in Neural Information Processing Systems 33, 6840–6851."}]},{"#name":"bib-reference","$":{"id":"b21"},"$$":[{"#name":"label","_":"Hou et al., 2023"},{"#name":"reference","$":{"id":"sb21","refId":"21"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Hou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Guo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Liu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.D."},{"#name":"surname","_":"Lin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Fan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Wei"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Lin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Jiang"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Deep-learning-enabled brain hemodynamic mapping using resting-state fMRI"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"NPJ Digit. Med."}]},{"#name":"volume-nr","_":"6"}]},{"#name":"issue-nr","_":"1"},{"#name":"date","_":"2023"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"116"}]}]}]},{"#name":"source-text","$":{"id":"afs21"},"_":"Hou, X., Guo, P., Wang, P., Liu, P., Lin, D.D., Fan, H., Li, Y., Wei, Z., Lin, Z., Jiang, D., et al., 2023. Deep-learning-enabled brain hemodynamic mapping using resting-state fMRI. NPJ Digital Medicine 6, 116."}]},{"#name":"bib-reference","$":{"id":"b22"},"$$":[{"#name":"label","_":"Ingalhalikar et al., 2021"},{"#name":"reference","$":{"id":"sb22","refId":"22"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Ingalhalikar"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Shinde"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Karmarkar"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Rajan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Rangaprakash"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Deshpande"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Functional connectivity-based prediction of autism on site harmonized ABIDE dataset"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Biomed. Eng."}]},{"#name":"volume-nr","_":"68"}]},{"#name":"issue-nr","_":"12"},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"3628"},{"#name":"last-page","_":"3637"}]}]}]},{"#name":"source-text","$":{"id":"afs22"},"_":"Ingalhalikar, M., Shinde, S., Karmarkar, A., Rajan, A., Rangaprakash, D., Deshpande, G., 2021. Functional connectivity-based prediction of Autism on site harmonized ABIDE dataset. IEEE Transactions on Biomedical Engineering 68, 3628–3637."}]},{"#name":"bib-reference","$":{"id":"b23"},"$$":[{"#name":"label","_":"Jang et al., 2016"},{"#name":"reference","$":{"id":"sb23","refId":"23"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Jang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Gu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Poole"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Categorical reparameterization with gumbel-softmax"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2016"}]}]},{"#name":"comment","$$":[{"#name":"__text__","_":"arXiv preprint "},{"#name":"inter-ref","$":{"id":"interref10","href":"arxiv:1611.01144","role":"http://www.elsevier.com/xml/linking-roles/preprint","type":"simple"},"_":"arXiv:1611.01144"}]}]},{"#name":"source-text","$":{"id":"afs23"},"_":"Jang, E., Gu, S., Poole, B., 2016. Categorical reparameterization with gumbel-softmax. arXiv preprint arXiv:1611.01144 ."}]},{"#name":"bib-reference","$":{"id":"b24"},"$$":[{"#name":"label","_":"Jiang et al., 2024"},{"#name":"other-ref","$":{"id":"sb24","refId":"24"},"$$":[{"#name":"textref","_":"Jiang, Y., Yang, Y., Xia, L., Huang, C., 2024. DiffKG: Knowledge Graph Diffusion Model for Recommendation. In: Proceedings of the 17th ACM International Conference on Web Search and Data Mining. pp. 313–321."}]}]},{"#name":"bib-reference","$":{"id":"b25"},"$$":[{"#name":"label","_":"Kim et al., 2021"},{"#name":"reference","$":{"id":"sb25","refId":"25"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"B.H."},{"#name":"surname","_":"Kim"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J.C."},{"#name":"surname","_":"Ye"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J.J."},{"#name":"surname","_":"Kim"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Learning dynamic graph representation of brain connectome with spatio-temporal attention"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"34"}]},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"4314"},{"#name":"last-page","_":"4327"}]}]}]},{"#name":"source-text","$":{"id":"afs25"},"_":"Kim, B.H., Ye, J.C., Kim, J.J., 2021. Learning dynamic graph representation of brain connectome with spatio-temporal attention. Advances in Neural Information Processing Systems 34, 4314–4327."}]},{"#name":"bib-reference","$":{"id":"b26"},"$$":[{"#name":"label","_":"Kingma and Ba, 2014"},{"#name":"reference","$":{"id":"sb26","refId":"26"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"D.P."},{"#name":"surname","_":"Kingma"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Ba"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Adam: A method for stochastic optimization"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2014"}]}]},{"#name":"comment","$$":[{"#name":"__text__","_":"arXiv preprint "},{"#name":"inter-ref","$":{"id":"interref11","href":"arxiv:1412.6980","role":"http://www.elsevier.com/xml/linking-roles/preprint","type":"simple"},"_":"arXiv:1412.6980"}]}]},{"#name":"source-text","$":{"id":"afs27"},"_":"Kingma, D.P., Ba, J., 2014. Adam: A method for stochastic optimization. arXiv preprint arXiv:1412.6980 ."}]},{"#name":"bib-reference","$":{"id":"b27"},"$$":[{"#name":"label","_":"Kingma et al., 2021"},{"#name":"reference","$":{"id":"sb27","refId":"27"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Kingma"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Salimans"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Poole"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Ho"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Variational diffusion models"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"34"}]},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"21696"},{"#name":"last-page","_":"21707"}]}]}]},{"#name":"source-text","$":{"id":"afs26"},"_":"Kingma, D., Salimans, T., Poole, B., Ho, J., 2021. Variational diffusion models. Advances in Neural Information Processing Systems 34, 21696–21707."}]},{"#name":"bib-reference","$":{"id":"b28"},"$$":[{"#name":"label","_":"Kipf and Welling, 2016"},{"#name":"reference","$":{"id":"sb28","refId":"28"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"T.N."},{"#name":"surname","_":"Kipf"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Welling"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Semi-supervised classification with graph convolutional networks"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2016"}]}]},{"#name":"comment","$$":[{"#name":"__text__","_":"arXiv preprint "},{"#name":"inter-ref","$":{"id":"interref12","href":"arxiv:1609.02907","role":"http://www.elsevier.com/xml/linking-roles/preprint","type":"simple"},"_":"arXiv:1609.02907"}]}]},{"#name":"source-text","$":{"id":"afs28"},"_":"Kipf, T.N., Welling, M., 2016. Semi-supervised classification with graph convolutional networks. arXiv preprint arXiv:1609.02907 ."}]},{"#name":"bib-reference","$":{"id":"b29"},"$$":[{"#name":"label","_":"Li et al., 2020"},{"#name":"reference","$":{"id":"sb29","refId":"29"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Gu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"N."},{"#name":"surname","_":"Dvornek"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L.H."},{"#name":"surname","_":"Staib"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Ventola"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J.S."},{"#name":"surname","_":"Duncan"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Multi-site fMRI analysis using privacy-preserving federated learning and domain adaptation: ABIDE results"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Med. Image Anal."}]},{"#name":"volume-nr","_":"65"}]},{"#name":"date","_":"2020"}]},{"#name":"article-number","_":"101765"}]}]},{"#name":"source-text","$":{"id":"afs30"},"_":"Li, X., Gu, Y., Dvornek, N., Staib, L.H., Ventola, P., Duncan, J.S., 2020. Multi-site fMRI analysis using privacy-preserving federated learning and domain adaptation: ABIDE results. Medical Image Analysis 65, 101765."}]},{"#name":"bib-reference","$":{"id":"b30"},"$$":[{"#name":"label","_":"Li et al., 2023"},{"#name":"reference","$":{"id":"sb30","refId":"30"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Srinivasan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Zhuo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Cui"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R.E."},{"#name":"surname","_":"Gur"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R.C."},{"#name":"surname","_":"Gur"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.J."},{"#name":"surname","_":"Oathes"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Davatzikos"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T.D."},{"#name":"surname","_":"Satterthwaite"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Fan"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Computing personalized brain functional networks from fMRI using self-supervised deep learning"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Med. Image Anal."}]},{"#name":"volume-nr","_":"85"}]},{"#name":"date","_":"2023"}]},{"#name":"article-number","_":"102756"}]}]},{"#name":"source-text","$":{"id":"afs29"},"_":"Li, H., Srinivasan, D., Zhuo, C., Cui, Z., Gur, R.E., Gur, R.C., Oathes, D.J., Davatzikos, C., Satterthwaite, T.D., Fan, Y., 2023. Computing personalized brain functional networks from fMRI using self-supervised deep learning. Medical Image Analysis 85, 102756."}]},{"#name":"bib-reference","$":{"id":"b31"},"$$":[{"#name":"label","_":"Liao et al., 2019"},{"#name":"reference","$":{"id":"sb31","refId":"31"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Liao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Song"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Hamilton"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.K."},{"#name":"surname","_":"Duvenaud"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Urtasun"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Zemel"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Efficient graph generation with graph recurrent attention networks"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"32"}]},{"#name":"date","_":"2019"}]}]}]},{"#name":"source-text","$":{"id":"afs31"},"_":"Liao, R., Li, Y., Song, Y., Wang, S., Hamilton, W., Duvenaud, D.K., Urtasun, R., Zemel, R., 2019. Efficient graph generation with graph recurrent attention networks. Advances in Neural Information Processing Systems 32."}]},{"#name":"bib-reference","$":{"id":"b32"},"$$":[{"#name":"label","_":"Liu et al., 2021"},{"#name":"reference","$":{"id":"sb32","refId":"32"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Liu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"F."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Hou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Mian"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Tang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Self-supervised learning: Generative or contrastive"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Knowl. Data Eng."}]},{"#name":"volume-nr","_":"35"}]},{"#name":"issue-nr","_":"1"},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"857"},{"#name":"last-page","_":"876"}]}]}]},{"#name":"source-text","$":{"id":"afs32"},"_":"Liu, X., Zhang, F., Hou, Z., Mian, L., Wang, Z., Zhang, J., Tang, J., 2021. Self-supervised learning: Generative or contrastive. IEEE Transactions on Knowledge and Data Engineering 35, 857–876."}]},{"#name":"bib-reference","$":{"id":"b33"},"$$":[{"#name":"label","_":"Luo et al., 2022"},{"#name":"reference","$":{"id":"sb33","refId":"33"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Luo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Su"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Peng"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Peng"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Ma"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Antigen-specific antibody design and optimization with diffusion-based generative models for protein structures"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"35"}]},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"9754"},{"#name":"last-page","_":"9767"}]}]}]},{"#name":"source-text","$":{"id":"afs33"},"_":"Luo, S., Su, Y., Peng, X., Wang, S., Peng, J., Ma, J., 2022. Antigen-specific antibody design and optimization with diffusion-based generative models for protein structures. Advances in Neural Information Processing Systems 35, 9754–9767."}]},{"#name":"bib-reference","$":{"id":"b34"},"$$":[{"#name":"label","_":"Mao et al., 2019"},{"#name":"reference","$":{"id":"sb34","refId":"34"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Mao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Su"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Xu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Huang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Yue"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Sun"}]},{"#name":"author","$$":[{"#name":"given-name","_":"N."},{"#name":"surname","_":"Xiong"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Spatio-temporal deep learning method for adhd fMRI classification"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Inform. Sci."}]},{"#name":"volume-nr","_":"499"}]},{"#name":"date","_":"2019"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1"},{"#name":"last-page","_":"11"}]}]}]},{"#name":"source-text","$":{"id":"afs34"},"_":"Mao, Z., Su, Y., Xu, G., Wang, X., Huang, Y., Yue, W., Sun, L., Xiong, N., 2019. Spatio-temporal deep learning method for adhd fMRI classification. Information Sciences 499, 1–11."}]},{"#name":"bib-reference","$":{"id":"b35"},"$$":[{"#name":"label","_":"Myung et al., 2016"},{"#name":"reference","$":{"id":"sb35","refId":"35"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Myung"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Han"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Fava"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Mischoulon"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Papakostas"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Heo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"K."},{"#name":"surname","_":"Kim"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Kim"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Kim"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Kim"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Reduced frontal-subcortical white matter connectivity in association with suicidal ideation in major depressive disorder"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Transl. Psychiatry"}]},{"#name":"volume-nr","_":"6"}]},{"#name":"issue-nr","_":"6"},{"#name":"date","_":"2016"}]}]},{"#name":"comment","_":"e835–e835"}]},{"#name":"source-text","$":{"id":"afs35"},"_":"Myung, W., Han, C., Fava, M., Mischoulon, D., Papakostas, G., Heo, J., Kim, K., Kim, S., Kim, D., Kim, D., et al., 2016. Reduced frontal-subcortical white matter connectivity in association with suicidal ideation in major depressive disorder. Translational Psychiatry 6, e835–e835."}]},{"#name":"bib-reference","$":{"id":"b36"},"$$":[{"#name":"label","_":"Nebel et al., 2022"},{"#name":"reference","$":{"id":"sb36","refId":"36"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"M.B."},{"#name":"surname","_":"Nebel"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.E."},{"#name":"surname","_":"Lidstone"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Benkeser"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S.H."},{"#name":"surname","_":"Mostofsky"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B.B."},{"#name":"surname","_":"Risk"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Accounting for motion in resting-state fMRI: What part of the spectrum are we characterizing in autism spectrum disorder?"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Neuroimage"}]},{"#name":"volume-nr","_":"257"}]},{"#name":"date","_":"2022"}]},{"#name":"article-number","_":"119296"}]}]},{"#name":"source-text","$":{"id":"afs36"},"_":"Nebel, M.B., Lidstone, D.E., Wang, L., Benkeser, D., Mostofsky, S.H., Risk, B.B., 2022. Accounting for motion in resting-state fMRI: What part of the spectrum are we characterizing in autism spectrum disorder? NeuroImage 257, 119296."}]},{"#name":"bib-reference","$":{"id":"b37"},"$$":[{"#name":"label","_":"Oh et al., 2020"},{"#name":"reference","$":{"id":"sb37","refId":"37"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Oh"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Han"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Jeong"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Time-series data augmentation based on interpolation"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Procedia Comput. Sci."}]},{"#name":"volume-nr","_":"175"}]},{"#name":"date","_":"2020"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"64"},{"#name":"last-page","_":"71"}]}]}]},{"#name":"source-text","$":{"id":"afs37"},"_":"Oh, C., Han, S., Jeong, J., 2020. Time-series data augmentation based on interpolation. Procedia Computer Science 175, 64–71."}]},{"#name":"bib-reference","$":{"id":"b38"},"$$":[{"#name":"label","_":"Paszke et al., 2017"},{"#name":"reference","$":{"id":"sb38","refId":"38"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Paszke"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Gross"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Chintala"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Chanan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Yang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"DeVito"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Lin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Desmaison"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Antiga"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Lerer"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Automatic differentiation in pytorch"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2017"}]}]}]},{"#name":"source-text","$":{"id":"afs38"},"_":"Paszke, A., Gross, S., Chintala, S., Chanan, G., Yang, E., DeVito, Z., Lin, Z., Desmaison, A., Antiga, L., Lerer, A., 2017. Automatic differentiation in Pytorch ."}]},{"#name":"bib-reference","$":{"id":"b39"},"$$":[{"#name":"label","_":"Pei et al., 2022"},{"#name":"reference","$":{"id":"sb39","refId":"39"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Pei"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Cao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Lv"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Data augmentation for fMRI-based functional connectivity and its application to cross-site ADHD classification"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Instrum. Meas."}]},{"#name":"volume-nr","_":"72"}]},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1"},{"#name":"last-page","_":"15"}]}]}]},{"#name":"source-text","$":{"id":"afs39"},"_":"Pei, S., Wang, C., Cao, S., Lv, Z., 2022. Data augmentation for fMRI-based functional connectivity and its application to cross-site ADHD classification. IEEE Transactions on Instrumentation and Measurement 72, 1–15."}]},{"#name":"bib-reference","$":{"id":"b40"},"$$":[{"#name":"label","_":"Peng et al., 2016"},{"#name":"reference","$":{"id":"sb40","refId":"40"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Peng"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Chen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Yin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Jia"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Q."},{"#name":"surname","_":"Gong"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Essential brain structural alterations in major depressive disorder: A voxel-wise meta-analysis on first episode, medication-naive patients"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"J. Affect. Disord."}]},{"#name":"volume-nr","_":"199"}]},{"#name":"date","_":"2016"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"114"},{"#name":"last-page","_":"123"}]}]}]},{"#name":"source-text","$":{"id":"afs41"},"_":"Peng, W., Chen, Z., Yin, L., Jia, Z., Gong, Q., 2016. Essential brain structural alterations in major depressive disorder: A voxel-wise meta-analysis on first episode, medication-naive patients. Journal of Affective Disorders 199, 114–123."}]},{"#name":"bib-reference","$":{"id":"b41"},"$$":[{"#name":"label","_":"Peng et al., 2022"},{"#name":"reference","$":{"id":"sb41","refId":"41"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Peng"}]},{"#name":"author","$$":[{"#name":"given-name","_":"N."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Xu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Zhu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Li"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"GATE: Graph CCA for temporal self-supervised learning for label-efficient fMRI analysis"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Med. Imaging"}]},{"#name":"volume-nr","_":"42"}]},{"#name":"issue-nr","_":"2"},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"391"},{"#name":"last-page","_":"402"}]}]}]},{"#name":"source-text","$":{"id":"afs40"},"_":"Peng, L., Wang, N., Xu, J., Zhu, X., Li, X., 2022. GATE: Graph CCA for temporal self-supervised learning for label-efficient fMRI analysis. IEEE Transactions on Medical Imaging 42, 391–402."}]},{"#name":"bib-reference","$":{"id":"b42"},"$$":[{"#name":"label","_":"Perez et al., 2018"},{"#name":"reference","$":{"id":"sb42","refId":"42"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Perez"}]},{"#name":"author","$$":[{"#name":"given-name","_":"F."},{"#name":"surname","_":"Strub"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"De Vries"}]},{"#name":"author","$$":[{"#name":"given-name","_":"V."},{"#name":"surname","_":"Dumoulin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Courville"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Film: Visual reasoning with a general conditioning layer"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"book-series","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Proceedings of the AAAI Conference on Artificial Intelligence"}]},{"#name":"volume-nr","_":"vol. 32"}]}]},{"#name":"date","_":"2018"}]}]}]},{"#name":"source-text","$":{"id":"afs42"},"_":"Perez, E., Strub, F., De Vries, H., Dumoulin, V., Courville, A., 2018. Film: Visual reasoning with a general conditioning layer, in: Proceedings of the AAAI Conference on Artificial Intelligence."}]},{"#name":"bib-reference","$":{"id":"b43"},"$$":[{"#name":"label","_":"Postema et al., 2019"},{"#name":"reference","$":{"id":"sb43","refId":"43"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"M.C."},{"#name":"surname","_":"Postema"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Van Rooij"}]},{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Anagnostou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Arango"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Auzias"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Behrmann"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G.B."},{"#name":"surname","_":"Filho"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Calderoni"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Calvo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Daly"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Altered structural brain asymmetry in autism spectrum disorder in a study of 54 datasets"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Nature Commun."}]},{"#name":"volume-nr","_":"10"}]},{"#name":"issue-nr","_":"1"},{"#name":"date","_":"2019"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"4958"}]}]}]},{"#name":"source-text","$":{"id":"afs43"},"_":"Postema, M.C., Van Rooij, D., Anagnostou, E., Arango, C., Auzias, G., Behrmann, M., Filho, G.B., Calderoni, S., Calvo, R., Daly, E., et al., 2019. Altered structural brain asymmetry in autism spectrum disorder in a study of 54 datasets. Nature Communications 10, 4958."}]},{"#name":"bib-reference","$":{"id":"b44"},"$$":[{"#name":"label","_":"Rashid and Louis, 2019"},{"#name":"reference","$":{"id":"sb44","refId":"44"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"K.M."},{"#name":"surname","_":"Rashid"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Louis"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Window-warping: A time series data augmentation of IMU data for construction equipment activity identification"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"book-series","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"ISARC. Proceedings of the International Symposium on Automation and Robotics in Construction"}]},{"#name":"volume-nr","_":"vol. 36"}]}]},{"#name":"date","_":"2019"},{"#name":"publisher","$$":[{"#name":"name","_":"IAARC Publications"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"651"},{"#name":"last-page","_":"657"}]}]}]},{"#name":"source-text","$":{"id":"afs44"},"_":"Rashid, K.M., Louis, J., 2019. Window-warping: A time series data augmentation of IMU data for construction equipment activity identification, in: ISARC. Proceedings of the International Symposium on Automation and Robotics in Construction, IAARC Publications. pp. 651–657."}]},{"#name":"bib-reference","$":{"id":"b45"},"$$":[{"#name":"label","_":"Shi et al., 2021"},{"#name":"reference","$":{"id":"sb45","refId":"45"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Shi"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Luo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Xu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Tang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Learning gradient fields for molecular conformation generation"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"International Conference on Machine Learning"}]},{"#name":"date","_":"2021"},{"#name":"publisher","$$":[{"#name":"name","_":"PMLR"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"9558"},{"#name":"last-page","_":"9568"}]}]}]},{"#name":"source-text","$":{"id":"afs45"},"_":"Shi, C., Luo, S., Xu, M., Tang, J., 2021. Learning gradient fields for molecular conformation generation, in: International Conference on Machine Learning, PMLR. pp. 9558–9568."}]},{"#name":"bib-reference","$":{"id":"b46"},"$$":[{"#name":"label","_":"Shi et al., 2024"},{"#name":"reference","$":{"id":"sb46","refId":"46"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Shi"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Yao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Zhu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Lin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Ji"}]},{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Liu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Li"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Contrastive hierarchical augmentation learning for modeling cognitive and multimodal brain network"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Comput. Soc. Syst."}]}]},{"#name":"date","_":"2024"}]}]}]},{"#name":"source-text","$":{"id":"afs46"},"_":"Shi, G., Yao, Y., Zhu, Y., Lin, X., Ji, L., Liu, W., Li, X., 2024. Contrastive hierarchical augmentation learning for modeling cognitive and multimodal brain network. IEEE Transactions on Computational Social Systems ."}]},{"#name":"bib-reference","$":{"id":"b47"},"$$":[{"#name":"label","_":"Shirer et al., 2015"},{"#name":"reference","$":{"id":"sb47","refId":"47"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"W.R."},{"#name":"surname","_":"Shirer"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Jiang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C.M."},{"#name":"surname","_":"Price"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Ng"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M.D."},{"#name":"surname","_":"Greicius"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Optimization of rs-fMRI pre-processing for enhanced signal-noise separation, test-retest reliability, and group discrimination"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Neuroimage"}]},{"#name":"volume-nr","_":"117"}]},{"#name":"date","_":"2015"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"67"},{"#name":"last-page","_":"79"}]}]}]},{"#name":"source-text","$":{"id":"afs47"},"_":"Shirer, W.R., Jiang, H., Price, C.M., Ng, B., Greicius, M.D., 2015. Optimization of rs-fMRI pre-processing for enhanced signal-noise separation, test-retest reliability, and group discrimination. NeuroImage 117, 67–79."}]},{"#name":"bib-reference","$":{"id":"b48"},"$$":[{"#name":"label","_":"Song et al., 2021"},{"#name":"reference","$":{"id":"sb48","refId":"48"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X.M."},{"#name":"surname","_":"Song"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X.W."},{"#name":"surname","_":"Hu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Gao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Ju"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.Y."},{"#name":"surname","_":"Liu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Q.N."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Xue"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y.C."},{"#name":"surname","_":"Cai"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Bai"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Reduction of higher-order occipital GABA and impaired visual perception in acute major depressive disorder"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Mol. Psychiatry"}]},{"#name":"volume-nr","_":"26"}]},{"#name":"issue-nr","_":"11"},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"6747"},{"#name":"last-page","_":"6755"}]}]}]},{"#name":"source-text","$":{"id":"afs48"},"_":"Song, X.M., Hu, X.W., Li, Z., Gao, Y., Ju, X., Liu, D.Y., Wang, Q.N., Xue, C., Cai, Y.C., Bai, R., et al., 2021. Reduction of higher-order occipital GABA and impaired visual perception in acute major depressive disorder. Molecular Psychiatry 26, 6747–6755."}]},{"#name":"bib-reference","$":{"id":"b49"},"$$":[{"#name":"label","_":"Suresh et al., 2021"},{"#name":"reference","$":{"id":"sb49","refId":"49"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Suresh"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Hao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Neville"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Adversarial graph augmentation to improve graph contrastive learning"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"34"}]},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"15920"},{"#name":"last-page","_":"15933"}]}]}]},{"#name":"source-text","$":{"id":"afs49"},"_":"Suresh, S., Li, P., Hao, C., Neville, J., 2021. Adversarial graph augmentation to improve graph contrastive learning. Advances in Neural Information Processing Systems 34, 15920–15933."}]},{"#name":"bib-reference","$":{"id":"b50"},"$$":[{"#name":"label","_":"Tang et al., 2022"},{"#name":"reference","$":{"id":"sb50","refId":"50"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Tang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Ma"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Guo"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Fu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Huang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Zhan"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Contrastive brain network learning via hierarchical signed graph pooling model"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Neural Netw. Learn. Syst."}]},{"#name":"volume-nr","_":"35"}]},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"7363"},{"#name":"last-page","_":"7375"}]}]}]},{"#name":"source-text","$":{"id":"afs50"},"_":"Tang, H., Ma, G., Guo, L., Fu, X., Huang, H., Zhan, L., 2022. Contrastive brain network learning via hierarchical signed graph pooling model. IEEE Transactions on Neural Networks and Learning Systems 35, 7363–7375."}]},{"#name":"bib-reference","$":{"id":"b51"},"$$":[{"#name":"label","_":"Tian et al., 2020"},{"#name":"reference","$":{"id":"sb51","refId":"51"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Tian"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Sun"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Poole"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Krishnan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Schmid"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Isola"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"What makes for good views for contrastive learning?"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"33"}]},{"#name":"date","_":"2020"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"6827"},{"#name":"last-page","_":"6839"}]}]}]},{"#name":"source-text","$":{"id":"afs51"},"_":"Tian, Y., Sun, C., Poole, B., Krishnan, D., Schmid, C., Isola, P., 2020. What makes for good views for contrastive learning? Advances in Neural Information Processing Systems 33, 6827–6839."}]},{"#name":"bib-reference","$":{"id":"b52"},"$$":[{"#name":"label","_":"Velickovic et al., 2017"},{"#name":"reference","$":{"id":"sb52","refId":"52"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Velickovic"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Cucurull"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Casanova"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Romero"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Lio"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Bengio"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Graph attention networks"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Stat"}]},{"#name":"volume-nr","_":"1050"}]},{"#name":"issue-nr","_":"20"},{"#name":"date","_":"2017"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"10"},{"#name":"last-page","_":"48550"}]}]}]},{"#name":"source-text","$":{"id":"afs52"},"_":"Velickovic, P., Cucurull, G., Casanova, A., Romero, A., Lio, P., Bengio, Y., et al., 2017. Graph attention networks. Stat 1050, 10–48550."}]},{"#name":"bib-reference","$":{"id":"b53"},"$$":[{"#name":"label","_":"Vignac et al., 2022"},{"#name":"reference","$":{"id":"sb53","refId":"53"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Vignac"}]},{"#name":"author","$$":[{"#name":"given-name","_":"I."},{"#name":"surname","_":"Krawczuk"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Siraudin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"V."},{"#name":"surname","_":"Cevher"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Frossard"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Digress: Discrete denoising diffusion for graph generation"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2022"}]}]},{"#name":"comment","$$":[{"#name":"__text__","_":"arXiv preprint "},{"#name":"inter-ref","$":{"id":"interref13","href":"arxiv:2209.14734","role":"http://www.elsevier.com/xml/linking-roles/preprint","type":"simple"},"_":"arXiv:2209.14734"}]}]},{"#name":"source-text","$":{"id":"afs53"},"_":"Vignac, C., Krawczuk, I., Siraudin, A., Wang, B., Cevher, V., Frossard, P., 2022. Digress: Discrete denoising diffusion for graph generation. arXiv preprint arXiv:2209.14734 ."}]},{"#name":"bib-reference","$":{"id":"b54"},"$$":[{"#name":"label","_":"Wang et al., 2023"},{"#name":"reference","$":{"id":"sb54","refId":"54"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Chu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Q."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Cao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Qiao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Liu"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Unsupervised contrastive graph learning for resting-state functional MRI analysis and brain disorder detection"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Hum. Brain Mapp."}]},{"#name":"volume-nr","_":"44"}]},{"#name":"issue-nr","_":"17"},{"#name":"date","_":"2023"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"5672"},{"#name":"last-page","_":"5692"}]}]}]},{"#name":"source-text","$":{"id":"afs56"},"_":"Wang, X., Chu, Y., Wang, Q., Cao, L., Qiao, L., Zhang, L., Liu, M., 2023. Unsupervised contrastive graph learning for resting-state functional MRI analysis and brain disorder detection. Human Brain Mapping 44, 5672–5692."}]},{"#name":"bib-reference","$":{"id":"b55"},"$$":[{"#name":"label","_":"Wang and Isola, 2020"},{"#name":"reference","$":{"id":"sb55","refId":"55"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Isola"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Understanding contrastive representation learning through alignment and uniformity on the hypersphere"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"International Conference on Machine Learning"}]},{"#name":"date","_":"2020"},{"#name":"publisher","$$":[{"#name":"name","_":"PMLR"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"9929"},{"#name":"last-page","_":"9939"}]}]}]},{"#name":"source-text","$":{"id":"afs55"},"_":"Wang, T., Isola, P., 2020. Understanding contrastive representation learning through alignment and uniformity on the hypersphere, in: International Conference on Machine Learning, PMLR. pp. 9929–9939."}]},{"#name":"bib-reference","$":{"id":"b56"},"$$":[{"#name":"label","_":"Wang et al., 2024"},{"#name":"reference","$":{"id":"sb56","refId":"56"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"Q."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Fang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P.T."},{"#name":"surname","_":"Yap"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Zhu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H.J."},{"#name":"surname","_":"Li"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Qiao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Liu"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Leveraging brain modularity prior for interpretable representation learning of fMRI"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Biomed. Eng."}]}]},{"#name":"date","_":"2024"}]}]}]},{"#name":"source-text","$":{"id":"afs54"},"_":"Wang, Q., Wang, W., Fang, Y., Yap, P.T., Zhu, H., Li, H.J., Qiao, L., Liu, M., 2024. Leveraging brain modularity prior for interpretable representation learning of fMRI. IEEE Transactions on Biomedical Engineering ."}]},{"#name":"bib-reference","$":{"id":"b57"},"$$":[{"#name":"label","_":"Wang et al., 2022"},{"#name":"reference","$":{"id":"sb57","refId":"57"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Yao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"I."},{"#name":"surname","_":"Rekik"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Zhang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Contrastive functional connectivity graph learning for population-based fMRI classification"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"International Conference on Medical Image Computing and Computer-Assisted Intervention"}]},{"#name":"date","_":"2022"},{"#name":"publisher","$$":[{"#name":"name","_":"Springer"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"221"},{"#name":"last-page","_":"230"}]}]}]},{"#name":"source-text","$":{"id":"afs57"},"_":"Wang, X., Yao, L., Rekik, I., Zhang, Y., 2022. Contrastive functional connectivity graph learning for population-based fMRI classification, in: International Conference on Medical Image Computing and Computer-Assisted Intervention, Springer. pp. 221–230."}]},{"#name":"bib-reference","$":{"id":"b58"},"$$":[{"#name":"label","_":"Weiner et al., 2013"},{"#name":"reference","$":{"id":"sb58","refId":"58"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"M.W."},{"#name":"surname","_":"Weiner"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D.P."},{"#name":"surname","_":"Veitch"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P.S."},{"#name":"surname","_":"Aisen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L.A."},{"#name":"surname","_":"Beckett"}]},{"#name":"author","$$":[{"#name":"given-name","_":"N.J."},{"#name":"surname","_":"Cairns"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R.C."},{"#name":"surname","_":"Green"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Harvey"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C.R."},{"#name":"surname","_":"Jack"}]},{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Jagust"}]},{"#name":"author","$$":[{"#name":"given-name","_":"E."},{"#name":"surname","_":"Liu"}]},{"#name":"et-al"}]},{"#name":"title","$$":[{"#name":"maintitle","_":"The alzheimer’s disease neuroimaging initiative: A review of papers published since its inception"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Alzheimer’s & Dementia"}]},{"#name":"volume-nr","_":"9"}]},{"#name":"issue-nr","_":"5"},{"#name":"date","_":"2013"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"e111"},{"#name":"last-page","_":"e194"}]}]}]},{"#name":"source-text","$":{"id":"afs58"},"_":"Weiner, M.W., Veitch, D.P., Aisen, P.S., Beckett, L.A., Cairns, N.J., Green, R.C., Harvey, D., Jack, C.R., Jagust, W., Liu, E., et al., 2013. The Alzheimer’s disease neuroimaging initiative: A review of papers published since its inception. Alzheimer’s & Dementia 9, e111–e194."}]},{"#name":"bib-reference","$":{"id":"b59"},"$$":[{"#name":"label","_":"Wen et al., 2023"},{"#name":"reference","$":{"id":"sb59","refId":"59"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Wen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Cao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Liu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Yang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"F."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"O.R."},{"#name":"surname","_":"Zaiane"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Graph self-supervised learning with application to brain networks analysis"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE J. Biomed. Health Inf."}]}]},{"#name":"date","_":"2023"}]}]}]},{"#name":"source-text","$":{"id":"afs59"},"_":"Wen, G., Cao, P., Liu, L., Yang, J., Zhang, X., Wang, F., Zaiane, O.R., 2023. Graph self-supervised learning with application to brain networks analysis. IEEE Journal of Biomedical and Health Informatics ."}]},{"#name":"bib-reference","$":{"id":"b60"},"$$":[{"#name":"label","_":"Wu et al., 2024"},{"#name":"reference","$":{"id":"sb60","refId":"60"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Wu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Fu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Fang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Yang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Xiong"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Liu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Xu"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Medsegdiff: Medical image segmentation with diffusion probabilistic model"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Medical Imaging with Deep Learning"}]},{"#name":"date","_":"2024"},{"#name":"publisher","$$":[{"#name":"name","_":"PMLR"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1623"},{"#name":"last-page","_":"1639"}]}]}]},{"#name":"source-text","$":{"id":"afs60"},"_":"Wu, J., Fu, R., Fang, H., Zhang, Y., Yang, Y., Xiong, H., Liu, H., Xu, Y., 2024. Medsegdiff: Medical image segmentation with diffusion probabilistic model, in: Medical Imaging with Deep Learning, PMLR. pp. 1623–1639."}]},{"#name":"bib-reference","$":{"id":"b61"},"$$":[{"#name":"label","_":"Xia et al., 2021"},{"#name":"reference","$":{"id":"sb61","refId":"61"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"F."},{"#name":"surname","_":"Xia"}]},{"#name":"author","$$":[{"#name":"given-name","_":"K."},{"#name":"surname","_":"Sun"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Yu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"A."},{"#name":"surname","_":"Aziz"}]},{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Wan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Pan"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Liu"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Graph learning: A survey"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Artif. Intell."}]},{"#name":"volume-nr","_":"2"}]},{"#name":"issue-nr","_":"2"},{"#name":"date","_":"2021"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"109"},{"#name":"last-page","_":"127"}]}]}]},{"#name":"source-text","$":{"id":"afs61"},"_":"Xia, F., Sun, K., Yu, S., Aziz, A., Wan, L., Pan, S., Liu, H., 2021. Graph learning: A survey. IEEE Transactions on Artificial Intelligence 2, 109–127."}]},{"#name":"bib-reference","$":{"id":"b62"},"$$":[{"#name":"label","_":"Xia et al., 2013"},{"#name":"reference","$":{"id":"sb62","refId":"62"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Xia"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"He"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"BrainNet viewer: A network visualization tool for human brain connectomics"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"PLoS One"}]},{"#name":"volume-nr","_":"8"}]},{"#name":"issue-nr","_":"7"},{"#name":"date","_":"2013"}]},{"#name":"article-number","_":"e68910"}]}]},{"#name":"source-text","$":{"id":"afs62"},"_":"Xia, M., Wang, J., He, Y., 2013. BrainNet Viewer: A network visualization tool for human brain connectomics. PloS One 8, e68910."}]},{"#name":"bib-reference","$":{"id":"b63"},"$$":[{"#name":"label","_":"Yang et al., 2023"},{"#name":"reference","$":{"id":"sb63","refId":"63"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"L."},{"#name":"surname","_":"Yang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Song"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Hong"}]},{"#name":"author","$$":[{"#name":"given-name","_":"R."},{"#name":"surname","_":"Xu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Zhao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"W."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Cui"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M.H."},{"#name":"surname","_":"Yang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Diffusion models: A comprehensive survey of methods and applications"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"ACM Comput. Surv."}]},{"#name":"volume-nr","_":"56"}]},{"#name":"issue-nr","_":"4"},{"#name":"date","_":"2023"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"1"},{"#name":"last-page","_":"39"}]}]}]},{"#name":"source-text","$":{"id":"afs63"},"_":"Yang, L., Zhang, Z., Song, Y., Hong, S., Xu, R., Zhao, Y., Zhang, W., Cui, B., Yang, M.H., 2023. Diffusion models: A comprehensive survey of methods and applications. ACM Computing Surveys 56, 1–39."}]},{"#name":"bib-reference","$":{"id":"b64"},"$$":[{"#name":"label","_":"Yin et al., 2022"},{"#name":"reference","$":{"id":"sb64","refId":"64"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Yin"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Q."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Huang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Xiong"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Zhang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Autogcl: Automated graph contrastive learning via learnable view generators"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"book-series","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Proceedings of the AAAI Conference on Artificial Intelligence"}]},{"#name":"volume-nr","_":"vol. 36"}]}]},{"#name":"date","_":"2022"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"8892"},{"#name":"last-page","_":"8900"}]}]}]},{"#name":"source-text","$":{"id":"afs64"},"_":"Yin, Y., Wang, Q., Huang, S., Xiong, H., Zhang, X., 2022. Autogcl: Automated graph contrastive learning via learnable view generators, in: Proceedings of the AAAI Conference on Artificial Intelligence, pp. 8892–8900."}]},{"#name":"bib-reference","$":{"id":"b65"},"$$":[{"#name":"label","_":"You et al., 2020"},{"#name":"reference","$":{"id":"sb65","refId":"65"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"You"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Chen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Sui"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Chen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Shen"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Graph contrastive learning with augmentations"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Adv. Neural Inf. Process. Syst."}]},{"#name":"volume-nr","_":"33"}]},{"#name":"date","_":"2020"}]},{"#name":"pages","$$":[{"#name":"first-page","_":"5812"},{"#name":"last-page","_":"5823"}]}]}]},{"#name":"source-text","$":{"id":"afs65"},"_":"You, Y., Chen, T., Sui, Y., Chen, T., Wang, Z., Shen, Y., 2020. Graph contrastive learning with augmentations. Advances in Neural Information Processing Systems 33, 5812–5823."}]},{"#name":"bib-reference","$":{"id":"b66"},"$$":[{"#name":"label","_":"Zhang et al., 2023a"},{"#name":"reference","$":{"id":"sb66","refId":"66"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"S."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Chen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Shen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"B."},{"#name":"surname","_":"Ren"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Z."},{"#name":"surname","_":"Yu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Yang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Jiang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"D."},{"#name":"surname","_":"Shen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Zhou"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X.Y."},{"#name":"surname","_":"Zhang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A-GCL: Adversarial graph contrastive learning for fMRI analysis to diagnose neurodevelopmental disorders"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"Med. Image Anal."}]},{"#name":"volume-nr","_":"90"}]},{"#name":"date","_":"2023"}]},{"#name":"article-number","_":"102932"}]}]},{"#name":"source-text","$":{"id":"afs68"},"_":"Zhang, S., Chen, X., Shen, X., Ren, B., Yu, Z., Yang, H., Jiang, X., Shen, D., Zhou, Y., Zhang, X.Y., 2023c. A-GCL: Adversarial graph contrastive learning for fMRI analysis to diagnose neurodevelopmental disorders. Medical Image Analysis 90, 102932."}]},{"#name":"bib-reference","$":{"id":"b67"},"$$":[{"#name":"label","_":"Zhang et al., 2023b"},{"#name":"reference","$":{"id":"sb67","refId":"67"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Qamar"}]},{"#name":"author","$$":[{"#name":"given-name","_":"T."},{"#name":"surname","_":"Kang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y."},{"#name":"surname","_":"Jung"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"S.H."},{"#name":"surname","_":"Bae"}]},{"#name":"author","$$":[{"#name":"given-name","_":"C."},{"#name":"surname","_":"Zhang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"A survey on graph diffusion models: Generative AI in science for molecule, protein and material"}]}]},{"#name":"host","$$":[{"#name":"book","$$":[{"#name":"date","_":"2023"}]}]},{"#name":"comment","$$":[{"#name":"__text__","_":"arXiv preprint "},{"#name":"inter-ref","$":{"id":"interref14","href":"arxiv:2304.01565","role":"http://www.elsevier.com/xml/linking-roles/preprint","type":"simple"},"_":"arXiv:2304.01565"}]}]},{"#name":"source-text","$":{"id":"afs66"},"_":"Zhang, M., Qamar, M., Kang, T., Jung, Y., Zhang, C., Bae, S.H., Zhang, C., 2023a. A survey on graph diffusion models: Generative AI in science for molecule, protein and material. arXiv preprint arXiv:2304.01565 ."}]},{"#name":"bib-reference","$":{"id":"b68"},"$$":[{"#name":"label","_":"Zhang et al., 2023c"},{"#name":"reference","$":{"id":"sb68","refId":"68"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"G."},{"#name":"surname","_":"Wen"}]},{"#name":"author","$$":[{"#name":"given-name","_":"P."},{"#name":"surname","_":"Cao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Yang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Zhang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"X."},{"#name":"surname","_":"Zhu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"O.R."},{"#name":"surname","_":"Zaiane"}]},{"#name":"author","$$":[{"#name":"given-name","_":"F."},{"#name":"surname","_":"Wang"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"BrainUSL: U nsupervised graph s tructure l earning for functional brain network analysis"}]}]},{"#name":"host","$$":[{"#name":"edited-book","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"International Conference on Medical Image Computing and Computer-Assisted Intervention"}]},{"#name":"date","_":"2023"},{"#name":"publisher","$$":[{"#name":"name","_":"Springer"}]}]},{"#name":"pages","$$":[{"#name":"first-page","_":"205"},{"#name":"last-page","_":"214"}]}]}]},{"#name":"source-text","$":{"id":"afs67"},"_":"Zhang, P., Wen, G., Cao, P., Yang, J., Zhang, J., Zhang, X., Zhu, X., Zaiane, O.R., Wang, F., 2023b. BrainUSL: U nsupervised graph S tructure L earning for functional brain network analysis, in: International Conference on Medical Image Computing and Computer-Assisted Intervention, Springer. pp. 205–214."}]},{"#name":"bib-reference","$":{"id":"b69"},"$$":[{"#name":"label","_":"Zhu et al., 2022"},{"#name":"reference","$":{"id":"sb69","refId":"69"},"$$":[{"#name":"contribution","$":{"langtype":"en"},"$$":[{"#name":"authors","$$":[{"#name":"author","$$":[{"#name":"given-name","_":"H."},{"#name":"surname","_":"Zhu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Wang"}]},{"#name":"author","$$":[{"#name":"given-name","_":"Y.P."},{"#name":"surname","_":"Zhao"}]},{"#name":"author","$$":[{"#name":"given-name","_":"M."},{"#name":"surname","_":"Lu"}]},{"#name":"author","$$":[{"#name":"given-name","_":"J."},{"#name":"surname","_":"Shi"}]}]},{"#name":"title","$$":[{"#name":"maintitle","_":"Contrastive multi-view composite graph convolutional networks based on contribution learning for autism spectrum disorder classification"}]}]},{"#name":"host","$$":[{"#name":"issue","$$":[{"#name":"series","$$":[{"#name":"title","$$":[{"#name":"maintitle","_":"IEEE Trans. Biomed. Eng."}]}]},{"#name":"date","_":"2022"}]}]}]},{"#name":"source-text","$":{"id":"afs69"},"_":"Zhu, H., Wang, J., Zhao, Y.P., Lu, M., Shi, J., 2022. Contrastive multi-view composite graph convolutional networks based on contribution learning for autism spectrum disorder classification. IEEE Transactions on Biomedical Engineering ."}]},{"#name":"bib-reference","$":{"id":"b70"},"$$":[{"#name":"label","_":"Zhu et al., 2021"},{"#name":"other-ref","$":{"id":"sb70","refId":"70"},"$$":[{"#name":"textref","_":"Zhu, Y., Xu, Y., Yu, F., Liu, Q., Wu, S., Wang, L., 2021. Graph contrastive learning with adaptive augmentation. In: Proceedings of the Web Conference 2021. pp. 2069–2080."}]}]}]}]}],"floats":[],"footnotes":[],"attachments":[],"sourceTextMap":{"1":"Amemiya, S., Takao, H., Hanaoka, S., Ohtomo, K., 2016. Global and structured waves of rs-fMRI signal identified as putative propagation of spontaneous neural activity. NeuroImage 133, 331–340.","2":"Bessadok, A., Mahjoub, M.A., Rekik, I., 2022. Graph neural networks in network neuroscience. IEEE Transactions on Pattern Analysis and Machine Intelligence 45, 5833–5848.","3":"Bijsterbosch, J., Smith, S.M., Beckmann, C., 2017. An introduction to resting state fMRI functional connectivity. Oxford University Press.","4":"Bondi, E., Maggioni, E., Brambilla, P., Delvecchio, G., 2023. A systematic review on the potential use of machine learning to classify major depressive disorder from healthy controls using resting state fMRI measures. Neuroscience & Biobehavioral Reviews 144, 104972.","6":"Chen, T., Kornblith, S., Norouzi, M., Hinton, G., 2020. A simple framework for contrastive learning of visual representations, in: International Conference on Machine Learning, PMLR. pp. 1597–1607.","7":"Cui, W., Du, J., Sun, M., Zhu, S., Zhao, S., Peng, Z., Tan, L., Li, Y., 2023. Dynamic multi-site graph convolutional network for autism spectrum disorder identification. Computers in Biology and Medicine 157, 106749.","8":"Dai, P., Lu, D., Shi, Y., Zhou, Y., Xiong, T., Zhou, X., Chen, Z., Zou, B., Tang, H., Huang, Z., et al., 2023. Classification of recurrent major depressive disorder using a new time series feature extraction method through multisite rs-fMRI data. Journal of Affective Disorders 339, 511–519.","9":"Demirel, B.U., Holz, C., 2024. Finding order in chaos: A novel data augmentation method for time series in contrastive learning. Advances in Neural Information Processing Systems 36.","10":"Dwivedi, V.P., Bresson, X., 2020. A generalization of Transformer networks to graphs. arXiv preprint arXiv:2012.09699 .","11":"Ecker, C., Bookheimer, S.Y., Murphy, D.G., 2015. Neuroimaging in autism spectrum disorder: Brain structure and function across the lifespan. The Lancet Neurology 14, 1121–1134.","12":"Ericsson, L., Gouk, H., Loy, C.C., Hospedales, T.M., 2022. Self-supervised representation learning: Introduction, advances, and challenges. IEEE Signal Processing Magazine 39, 42–62.","13":"Fang, Y., Wang, M., Potter, G.G., Liu, M., 2023. Unsupervised cross-domain functional MRI adaptation for automated major depressive disorder identification. Medical Image Analysis 84, 102707.","14":"Fedorov, A., Geenjaar, E., Wu, L., Sylvain, T., DeRamus, T.P., Luck, M., Misiura, M., Mittapalle, G., Hjelm, R.D., Plis, S.M., et al., 2024. Self-supervised multimodal learning for group inferences from MRI data: Discovering disorder-relevant brain regions and multimodal links. NeuroImage 285, 120485.","15":"Guan, H., Liu, M., 2021. Domain adaptation for medical image analysis: A survey. IEEE Transactions on Biomedical Engineering 69, 1173–1185.","16":"Guo, X., Zhao, L., 2022. A systematic survey on deep generative models for graph generation. IEEE Transactions on Pattern Analysis and Machine Intelligence 45, 5370–5390.","18":"Hebling Vieira, B., Dubois, J., Calhoun, V.D., Garrido Salmon, C.E., 2021. A deep learning based approach identifies regions more relevant than resting-state networks to the prediction of general intelligence from resting-state fMRI. Human Brain Mapping 42, 5873–5887.","19":"Hendrycks, D., Mazeika, M., Kadavath, S., Song, D., 2019. Using self-supervised learning can improve model robustness and uncertainty. Advances in Neural Information Processing Systems 32.","20":"Ho, J., Jain, A., Abbeel, P., 2020. Denoising diffusion probabilistic models. Advances in Neural Information Processing Systems 33, 6840–6851.","21":"Hou, X., Guo, P., Wang, P., Liu, P., Lin, D.D., Fan, H., Li, Y., Wei, Z., Lin, Z., Jiang, D., et al., 2023. Deep-learning-enabled brain hemodynamic mapping using resting-state fMRI. NPJ Digital Medicine 6, 116.","22":"Ingalhalikar, M., Shinde, S., Karmarkar, A., Rajan, A., Rangaprakash, D., Deshpande, G., 2021. Functional connectivity-based prediction of Autism on site harmonized ABIDE dataset. IEEE Transactions on Biomedical Engineering 68, 3628–3637.","23":"Jang, E., Gu, S., Poole, B., 2016. Categorical reparameterization with gumbel-softmax. arXiv preprint arXiv:1611.01144 .","25":"Kim, B.H., Ye, J.C., Kim, J.J., 2021. Learning dynamic graph representation of brain connectome with spatio-temporal attention. Advances in Neural Information Processing Systems 34, 4314–4327.","26":"Kingma, D.P., Ba, J., 2014. Adam: A method for stochastic optimization. arXiv preprint arXiv:1412.6980 .","27":"Kingma, D., Salimans, T., Poole, B., Ho, J., 2021. Variational diffusion models. Advances in Neural Information Processing Systems 34, 21696–21707.","28":"Kipf, T.N., Welling, M., 2016. Semi-supervised classification with graph convolutional networks. arXiv preprint arXiv:1609.02907 .","29":"Li, X., Gu, Y., Dvornek, N., Staib, L.H., Ventola, P., Duncan, J.S., 2020. Multi-site fMRI analysis using privacy-preserving federated learning and domain adaptation: ABIDE results. Medical Image Analysis 65, 101765.","30":"Li, H., Srinivasan, D., Zhuo, C., Cui, Z., Gur, R.E., Gur, R.C., Oathes, D.J., Davatzikos, C., Satterthwaite, T.D., Fan, Y., 2023. Computing personalized brain functional networks from fMRI using self-supervised deep learning. Medical Image Analysis 85, 102756.","31":"Liao, R., Li, Y., Song, Y., Wang, S., Hamilton, W., Duvenaud, D.K., Urtasun, R., Zemel, R., 2019. Efficient graph generation with graph recurrent attention networks. Advances in Neural Information Processing Systems 32.","32":"Liu, X., Zhang, F., Hou, Z., Mian, L., Wang, Z., Zhang, J., Tang, J., 2021. Self-supervised learning: Generative or contrastive. IEEE Transactions on Knowledge and Data Engineering 35, 857–876.","33":"Luo, S., Su, Y., Peng, X., Wang, S., Peng, J., Ma, J., 2022. Antigen-specific antibody design and optimization with diffusion-based generative models for protein structures. Advances in Neural Information Processing Systems 35, 9754–9767.","34":"Mao, Z., Su, Y., Xu, G., Wang, X., Huang, Y., Yue, W., Sun, L., Xiong, N., 2019. Spatio-temporal deep learning method for adhd fMRI classification. Information Sciences 499, 1–11.","35":"Myung, W., Han, C., Fava, M., Mischoulon, D., Papakostas, G., Heo, J., Kim, K., Kim, S., Kim, D., Kim, D., et al., 2016. Reduced frontal-subcortical white matter connectivity in association with suicidal ideation in major depressive disorder. Translational Psychiatry 6, e835–e835.","36":"Nebel, M.B., Lidstone, D.E., Wang, L., Benkeser, D., Mostofsky, S.H., Risk, B.B., 2022. Accounting for motion in resting-state fMRI: What part of the spectrum are we characterizing in autism spectrum disorder? NeuroImage 257, 119296.","37":"Oh, C., Han, S., Jeong, J., 2020. Time-series data augmentation based on interpolation. Procedia Computer Science 175, 64–71.","38":"Paszke, A., Gross, S., Chintala, S., Chanan, G., Yang, E., DeVito, Z., Lin, Z., Desmaison, A., Antiga, L., Lerer, A., 2017. Automatic differentiation in Pytorch .","39":"Pei, S., Wang, C., Cao, S., Lv, Z., 2022. Data augmentation for fMRI-based functional connectivity and its application to cross-site ADHD classification. IEEE Transactions on Instrumentation and Measurement 72, 1–15.","40":"Peng, W., Chen, Z., Yin, L., Jia, Z., Gong, Q., 2016. Essential brain structural alterations in major depressive disorder: A voxel-wise meta-analysis on first episode, medication-naive patients. Journal of Affective Disorders 199, 114–123.","41":"Peng, L., Wang, N., Xu, J., Zhu, X., Li, X., 2022. GATE: Graph CCA for temporal self-supervised learning for label-efficient fMRI analysis. IEEE Transactions on Medical Imaging 42, 391–402.","42":"Perez, E., Strub, F., De Vries, H., Dumoulin, V., Courville, A., 2018. Film: Visual reasoning with a general conditioning layer, in: Proceedings of the AAAI Conference on Artificial Intelligence.","43":"Postema, M.C., Van Rooij, D., Anagnostou, E., Arango, C., Auzias, G., Behrmann, M., Filho, G.B., Calderoni, S., Calvo, R., Daly, E., et al., 2019. Altered structural brain asymmetry in autism spectrum disorder in a study of 54 datasets. Nature Communications 10, 4958.","44":"Rashid, K.M., Louis, J., 2019. Window-warping: A time series data augmentation of IMU data for construction equipment activity identification, in: ISARC. Proceedings of the International Symposium on Automation and Robotics in Construction, IAARC Publications. pp. 651–657.","45":"Shi, C., Luo, S., Xu, M., Tang, J., 2021. Learning gradient fields for molecular conformation generation, in: International Conference on Machine Learning, PMLR. pp. 9558–9568.","46":"Shi, G., Yao, Y., Zhu, Y., Lin, X., Ji, L., Liu, W., Li, X., 2024. Contrastive hierarchical augmentation learning for modeling cognitive and multimodal brain network. IEEE Transactions on Computational Social Systems .","47":"Shirer, W.R., Jiang, H., Price, C.M., Ng, B., Greicius, M.D., 2015. Optimization of rs-fMRI pre-processing for enhanced signal-noise separation, test-retest reliability, and group discrimination. NeuroImage 117, 67–79.","48":"Song, X.M., Hu, X.W., Li, Z., Gao, Y., Ju, X., Liu, D.Y., Wang, Q.N., Xue, C., Cai, Y.C., Bai, R., et al., 2021. Reduction of higher-order occipital GABA and impaired visual perception in acute major depressive disorder. Molecular Psychiatry 26, 6747–6755.","49":"Suresh, S., Li, P., Hao, C., Neville, J., 2021. Adversarial graph augmentation to improve graph contrastive learning. Advances in Neural Information Processing Systems 34, 15920–15933.","50":"Tang, H., Ma, G., Guo, L., Fu, X., Huang, H., Zhan, L., 2022. Contrastive brain network learning via hierarchical signed graph pooling model. IEEE Transactions on Neural Networks and Learning Systems 35, 7363–7375.","51":"Tian, Y., Sun, C., Poole, B., Krishnan, D., Schmid, C., Isola, P., 2020. What makes for good views for contrastive learning? Advances in Neural Information Processing Systems 33, 6827–6839.","52":"Velickovic, P., Cucurull, G., Casanova, A., Romero, A., Lio, P., Bengio, Y., et al., 2017. Graph attention networks. Stat 1050, 10–48550.","53":"Vignac, C., Krawczuk, I., Siraudin, A., Wang, B., Cevher, V., Frossard, P., 2022. Digress: Discrete denoising diffusion for graph generation. arXiv preprint arXiv:2209.14734 .","54":"Wang, X., Chu, Y., Wang, Q., Cao, L., Qiao, L., Zhang, L., Liu, M., 2023. Unsupervised contrastive graph learning for resting-state functional MRI analysis and brain disorder detection. Human Brain Mapping 44, 5672–5692.","55":"Wang, T., Isola, P., 2020. Understanding contrastive representation learning through alignment and uniformity on the hypersphere, in: International Conference on Machine Learning, PMLR. pp. 9929–9939.","56":"Wang, Q., Wang, W., Fang, Y., Yap, P.T., Zhu, H., Li, H.J., Qiao, L., Liu, M., 2024. Leveraging brain modularity prior for interpretable representation learning of fMRI. IEEE Transactions on Biomedical Engineering .","57":"Wang, X., Yao, L., Rekik, I., Zhang, Y., 2022. Contrastive functional connectivity graph learning for population-based fMRI classification, in: International Conference on Medical Image Computing and Computer-Assisted Intervention, Springer. pp. 221–230.","58":"Weiner, M.W., Veitch, D.P., Aisen, P.S., Beckett, L.A., Cairns, N.J., Green, R.C., Harvey, D., Jack, C.R., Jagust, W., Liu, E., et al., 2013. The Alzheimer’s disease neuroimaging initiative: A review of papers published since its inception. Alzheimer’s & Dementia 9, e111–e194.","59":"Wen, G., Cao, P., Liu, L., Yang, J., Zhang, X., Wang, F., Zaiane, O.R., 2023. Graph self-supervised learning with application to brain networks analysis. IEEE Journal of Biomedical and Health Informatics .","60":"Wu, J., Fu, R., Fang, H., Zhang, Y., Yang, Y., Xiong, H., Liu, H., Xu, Y., 2024. Medsegdiff: Medical image segmentation with diffusion probabilistic model, in: Medical Imaging with Deep Learning, PMLR. pp. 1623–1639.","61":"Xia, F., Sun, K., Yu, S., Aziz, A., Wan, L., Pan, S., Liu, H., 2021. Graph learning: A survey. IEEE Transactions on Artificial Intelligence 2, 109–127.","62":"Xia, M., Wang, J., He, Y., 2013. BrainNet Viewer: A network visualization tool for human brain connectomics. PloS One 8, e68910.","63":"Yang, L., Zhang, Z., Song, Y., Hong, S., Xu, R., Zhao, Y., Zhang, W., Cui, B., Yang, M.H., 2023. Diffusion models: A comprehensive survey of methods and applications. ACM Computing Surveys 56, 1–39.","64":"Yin, Y., Wang, Q., Huang, S., Xiong, H., Zhang, X., 2022. Autogcl: Automated graph contrastive learning via learnable view generators, in: Proceedings of the AAAI Conference on Artificial Intelligence, pp. 8892–8900.","65":"You, Y., Chen, T., Sui, Y., Chen, T., Wang, Z., Shen, Y., 2020. Graph contrastive learning with augmentations. Advances in Neural Information Processing Systems 33, 5812–5823.","66":"Zhang, S., Chen, X., Shen, X., Ren, B., Yu, Z., Yang, H., Jiang, X., Shen, D., Zhou, Y., Zhang, X.Y., 2023c. A-GCL: Adversarial graph contrastive learning for fMRI analysis to diagnose neurodevelopmental disorders. Medical Image Analysis 90, 102932.","67":"Zhang, M., Qamar, M., Kang, T., Jung, Y., Zhang, C., Bae, S.H., Zhang, C., 2023a. A survey on graph diffusion models: Generative AI in science for molecule, protein and material. arXiv preprint arXiv:2304.01565 .","68":"Zhang, P., Wen, G., Cao, P., Yang, J., Zhang, J., Zhang, X., Zhu, X., Zaiane, O.R., Wang, F., 2023b. BrainUSL: U nsupervised graph S tructure L earning for functional brain network analysis, in: International Conference on Medical Image Computing and Computer-Assisted Intervention, Springer. pp. 205–214.","69":"Zhu, H., Wang, J., Zhao, Y.P., Lu, M., Shi, J., 2022. Contrastive multi-view composite graph convolutional networks based on contribution learning for autism spectrum disorder classification. IEEE Transactions on Biomedical Engineering ."}},"referenceLinks":{"external":[{"refId":1,"scopusHubEid":"2-s2.0-84962028769"},{"refId":4,"scopusHubEid":"2-s2.0-85145424769"},{"refId":7,"scopusHubEid":"2-s2.0-85149839695"},{"refId":8,"scopusHubEid":"2-s2.0-85165211782"},{"refId":11,"scopusHubEid":"2-s2.0-84944178004"},{"refId":12,"scopusHubEid":"2-s2.0-85129504426","crossRefDoi":"10.1109/msp.2021.3134634"},{"refId":13,"scopusHubEid":"2-s2.0-85143664485"},{"refId":14,"scopusHubEid":"2-s2.0-85181057252"},{"refId":18,"scopusHubEid":"2-s2.0-85116036757","crossRefDoi":"10.1002/hbm.25656"},{"refId":21,"scopusHubEid":"2-s2.0-85162924168","crossRefDoi":"10.33696/immunology.5.176"},{"refId":22,"scopusHubEid":"2-s2.0-85105879453","crossRefDoi":"10.1109/tbme.2021.3080259"},{"refId":25,"scopusHubEid":"2-s2.0-85129568575"},{"refId":27,"scopusHubEid":"2-s2.0-85124683180"},{"refId":29,"scopusHubEid":"2-s2.0-85087860824"},{"refId":30,"scopusHubEid":"2-s2.0-85146826531"},{"refId":32,"crossRefDoi":"10.3390/jof7100857"},{"refId":34,"scopusHubEid":"2-s2.0-85066265739"},{"refId":36,"scopusHubEid":"2-s2.0-85132455109"},{"refId":37,"scopusHubEid":"2-s2.0-85094591543"},{"refId":40,"scopusHubEid":"2-s2.0-84963946750"},{"refId":41,"scopusHubEid":"2-s2.0-85129661852","crossRefDoi":"10.1108/cdi-11-2021-0295"},{"refId":43,"scopusHubEid":"2-s2.0-85074287980"},{"refId":44,"scopusHubEid":"2-s2.0-85071496164"},{"refId":45,"scopusHubEid":"2-s2.0-85161275447"},{"refId":47,"scopusHubEid":"2-s2.0-84930631730"},{"refId":48,"scopusHubEid":"2-s2.0-85104803953","crossRefDoi":"10.1038/s41380-021-01090-5"},{"refId":49,"scopusHubEid":"2-s2.0-85128083600"},{"refId":54,"scopusHubEid":"2-s2.0-85169824741","crossRefDoi":"10.1002/hbm.26469"},{"refId":57,"crossRefDoi":"10.1007/978-3-031-16431-6_21"},{"refId":58,"scopusHubEid":"2-s2.0-84883552519"},{"refId":60,"scopusHubEid":"2-s2.0-85182370035","crossRefDoi":"10.1109/tce.2024.3352186"},{"refId":61,"scopusHubEid":"2-s2.0-85141058016","crossRefDoi":"10.1109/tai.2021.3076021"},{"refId":62,"scopusHubEid":"2-s2.0-84879833765","crossRefDoi":"10.1371/journal.pone.0068910"},{"refId":63,"crossRefDoi":"10.1504/ijaac.2023.10047051"},{"refId":64,"scopusHubEid":"2-s2.0-85135543993","crossRefDoi":"10.1609/aaai.v36i8.20871"},{"refId":66,"scopusHubEid":"2-s2.0-85169841225"},{"refId":68,"crossRefDoi":"10.1007/978-3-031-43993-3_20"}],"internal":[{"refId":1,"pii":"S105381191600238X","filesize":"4MB","pdf":{"urlType":"download","url":"/science/article/pii/S105381191600238X/pdfft?md5=6e35b79a2e0b5d3f013031f2f908f704&pid=1-s2.0-S105381191600238X-main.pdf"}},{"refId":4,"pii":"S0149763422004614","filesize":"1MB","pdf":{"urlType":"download","url":"/science/article/pii/S0149763422004614/pdfft?md5=85350ef51200a5252b22d661412bed64&pid=1-s2.0-S0149763422004614-main.pdf"}},{"refId":7,"pii":"S0010482523002147","filesize":"5MB","pdf":{"urlType":"download","url":"/science/article/pii/S0010482523002147/pdfft?md5=62176e668b0ad049d029317b3991ad98&pid=1-s2.0-S0010482523002147-main.pdf"}},{"refId":8,"pii":"S016503272300928X","filesize":"3MB","pdf":{"urlType":"download","url":"/science/article/pii/S016503272300928X/pdfft?md5=9ec67270973c9e9e76ce31cdb45fa4ff&pid=1-s2.0-S016503272300928X-main.pdf"}},{"refId":11,"pii":"S1474442215000502","filesize":"2MB","pdf":{"urlType":"download","url":"/science/article/pii/S1474442215000502/pdfft?md5=cd3041514550526b5ed0a142fe78ea02&pid=1-s2.0-S1474442215000502-main.pdf"}},{"refId":13,"pii":"S1361841522003358","filesize":"2MB","pdf":{"urlType":"download","url":"/science/article/pii/S1361841522003358/pdfft?md5=ef661fe88c477240b58291fbdaddfda8&pid=1-s2.0-S1361841522003358-main.pdf"}},{"refId":14,"pii":"S1053811923006353","filesize":"8MB","pdf":{"urlType":"download","url":"/science/article/pii/S1053811923006353/pdfft?md5=506a531143dc10b8fc56d8eee1386fb0&pid=1-s2.0-S1053811923006353-main.pdf"}},{"refId":29,"pii":"S1361841520301298","filesize":"4MB","pdf":{"urlType":"download","url":"/science/article/pii/S1361841520301298/pdfft?md5=298e7be02927947ceb6b29ec8346f399&pid=1-s2.0-S1361841520301298-main.pdf"}},{"refId":30,"pii":"S1361841523000178","filesize":"16MB","pdf":{"urlType":"download","url":"/science/article/pii/S1361841523000178/pdfft?md5=a5ea1e23f063173dc4831badc90299c9&pid=1-s2.0-S1361841523000178-main.pdf"}},{"refId":34,"pii":"S0020025519304475","filesize":"1MB","pdf":{"urlType":"download","url":"/science/article/pii/S0020025519304475/pdfft?md5=39bf52ccb4677dfc8a4341d427549952&pid=1-s2.0-S0020025519304475-main.pdf"}},{"refId":36,"pii":"S1053811922004153","filesize":"3MB","pdf":{"urlType":"download","url":"/science/article/pii/S1053811922004153/pdfft?md5=c9e242131104fa294b17a36758c53d64&pid=1-s2.0-S1053811922004153-main.pdf"}},{"refId":37,"pii":"S1877050920316914","filesize":"376KB","pdf":{"urlType":"download","url":"/science/article/pii/S1877050920316914/pdf?md5=61fc87095175770c01ecb1f4272202f9&pid=1-s2.0-S1877050920316914-main.pdf"}},{"refId":40,"pii":"S0165032716301070","filesize":"947KB","pdf":{"urlType":"download","url":"/science/article/pii/S0165032716301070/pdfft?md5=6d6d0b10cbbec0ad3e5e52e568175644&pid=1-s2.0-S0165032716301070-main.pdf"}},{"refId":47,"pii":"S105381191500395X","filesize":"4MB","pdf":{"urlType":"download","url":"/science/article/pii/S105381191500395X/pdfft?md5=2faa40f7fafb8d92bcd71beb8c9e7c99&pid=1-s2.0-S105381191500395X-main.pdf"}},{"refId":58,"pii":"S1552526013024291","filesize":"8MB","pdf":{"urlType":"download","url":"/science/article/pii/S1552526013024291/pdfft?md5=87e5988994fcea49ec3219de2bf00405&pid=1-s2.0-S1552526013024291-main.pdf"}},{"refId":66,"pii":"S1361841523001925","filesize":"4MB","pdf":{"urlType":"download","url":"/science/article/pii/S1361841523001925/pdfft?md5=5b5ce6aeffd45f58795af1d00da5d634&pid=1-s2.0-S1361841523001925-main.pdf"}}]},"refersTo":{},"referredToBy":{},"relatedContent":{"isModal":false,"isOpenSpecialIssueArticles":false,"isOpenVirtualSpecialIssueLink":false,"isOpenRecommendations":true,"isOpenSubstances":true,"citingArticles":[false,false,false,false,false,false],"recommendations":[false,false,false,false,false,false]},"seamlessAccess":{},"specialIssueArticles":{},"substances":{},"supplementaryFilesData":[],"tableOfContents":{"outlineTitle":"Outline","outline":[{"#name":"entry","$":{"class":"author","depth":"1","id":"d1e9156","type":"abstract"},"$$":[{"#name":"title","$":{"id":"d1e9157"},"_":"Abstract"}]},{"#name":"entry","$":{"class":"graphical","depth":"1","id":"d1e9168","type":"abstract"},"$$":[{"#name":"title","$":{"id":"d1e9169"},"_":"Graphical abstract"}]},{"#name":"entry","$":{"class":"author-highlights","depth":"1","id":"d1e9177","type":"abstract"},"$$":[{"#name":"title","$":{"id":"d1e9178"},"_":"Highlights"}]},{"#name":"entry","$":{"class":"keyword","depth":"1","id":"d1e9199","type":"keywords"},"$$":[{"#name":"title","$":{"id":"d1e9200"},"_":"Keywords"}]},{"#name":"entry","$":{"depth":"1","id":"sec1","type":"sections"},"$$":[{"#name":"label","_":"1"},{"#name":"title","$":{"id":"d1e9225"},"_":"Introduction"}]},{"#name":"entry","$":{"depth":"1","id":"sec2","type":"sections"},"$$":[{"#name":"label","_":"2"},{"#name":"title","$":{"id":"d1e9346"},"_":"Related work"},{"#name":"entry","$":{"depth":"2","id":"sec2.1"},"$$":[{"#name":"label","_":"2.1"},{"#name":"title","$":{"id":"d1e9351"},"_":"Self-supervised learning for fMRI analysis"}]},{"#name":"entry","$":{"depth":"2","id":"sec2.2"},"$$":[{"#name":"label","_":"2.2"},{"#name":"title","$":{"id":"d1e9409"},"_":"Graph diffusion model"}]}]},{"#name":"entry","$":{"depth":"1","id":"sec3","type":"sections"},"$$":[{"#name":"label","_":"3"},{"#name":"title","$":{"id":"d1e9446"},"_":"Materials and method"},{"#name":"entry","$":{"depth":"2","id":"sec3.1"},"$$":[{"#name":"label","_":"3.1"},{"#name":"title","$":{"id":"d1e9451"},"_":"Materials and data preprocessing"}]},{"#name":"entry","$":{"depth":"2","id":"sec3.2"},"$$":[{"#name":"label","_":"3.2"},{"#name":"title","$":{"id":"d1e10209"},"_":"Proposed method"},{"#name":"entry","$":{"depth":"3","id":"sec3.2.1"},"$$":[{"#name":"label","_":"3.2.1"},{"#name":"title","$":{"id":"d1e10226"},"_":"Pretext model"}]},{"#name":"entry","$":{"depth":"3","id":"sec3.2.2"},"$$":[{"#name":"label","_":"3.2.2"},{"#name":"title","$":{"id":"d1e13951"},"_":"Task-specific model"}]},{"#name":"entry","$":{"depth":"3","id":"sec3.2.3"},"$$":[{"#name":"label","_":"3.2.3"},{"#name":"title","$":{"id":"d1e13968"},"_":"Implementation details"}]}]}]},{"#name":"entry","$":{"depth":"1","id":"sec4","type":"sections"},"$$":[{"#name":"label","_":"4"},{"#name":"title","$":{"id":"d1e14144"},"_":"Experiments"},{"#name":"entry","$":{"depth":"2","id":"sec4.1"},"$$":[{"#name":"label","_":"4.1"},{"#name":"title","$":{"id":"d1e14149"},"_":"Experimental settings"}]},{"#name":"entry","$":{"depth":"2","id":"sec4.2"},"$$":[{"#name":"label","_":"4.2"},{"#name":"title","$":{"id":"d1e14179"},"_":"Competing methods"}]},{"#name":"entry","$":{"depth":"2","id":"sec4.3"},"$$":[{"#name":"label","_":"4.3"},{"#name":"title","$":{"id":"d1e14481"},"_":"Experimental results"}]},{"#name":"entry","$":{"depth":"2","id":"sec4.4"},"$$":[{"#name":"label","_":"4.4"},{"#name":"title","$":{"id":"d1e14615"},"_":"Visualization of graph diffusion results"}]},{"#name":"entry","$":{"depth":"2","id":"sec4.5"},"$$":[{"#name":"label","_":"4.5"},{"#name":"title","$":{"id":"d1e14668"},"_":"Visualization of learned features"}]}]},{"#name":"entry","$":{"depth":"1","id":"sec5","type":"sections"},"$$":[{"#name":"label","_":"5"},{"#name":"title","$":{"id":"d1e14713"},"_":"Discussion"},{"#name":"entry","$":{"depth":"2","id":"sec5.1"},"$$":[{"#name":"label","_":"5.1"},{"#name":"title","$":{"id":"d1e14718"},"_":"Ablation study"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.2"},"$$":[{"#name":"label","_":"5.2"},{"#name":"title","$":{"id":"d1e14765"},"_":"Influence of diffusion steps"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.3"},"$$":[{"#name":"label","_":"5.3"},{"#name":"title","$":{"id":"d1e14859"},"_":"Influence of trade-off parameter"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.4"},"$$":[{"#name":"label","_":"5.4"},{"#name":"title","$":{"id":"d1e14958"},"_":"Influence of added noise"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.5"},"$$":[{"#name":"label","_":"5.5"},{"#name":"title","$":{"id":"d1e15870"},"_":"Comparison with recent SOTA methods"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.6"},"$$":[{"#name":"label","_":"5.6"},{"#name":"title","$":{"id":"d1e15953"},"_":"Influence of contrastive learning strategy"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.7"},"$$":[{"#name":"label","_":"5.7"},{"#name":"title","$":{"id":"d1e16028"},"_":"Generalizability evaluation of GDA"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.8"},"$$":[{"#name":"label","_":"5.8"},{"#name":"title","$":{"id":"d1e16060"},"_":"Influence of feature encoder"}]},{"#name":"entry","$":{"depth":"2","id":"sec5.9"},"$$":[{"#name":"label","_":"5.9"},{"#name":"title","$":{"id":"d1e16109"},"_":"Limitations and future work"}]}]},{"#name":"entry","$":{"depth":"1","id":"sec6","type":"sections"},"$$":[{"#name":"label","_":"6"},{"#name":"title","$":{"id":"d1e16130"},"_":"Conclusion"}]},{"#name":"entry","$":{"depth":"1","id":"d1e16134","type":"sections"},"$$":[{"#name":"title","$":{"id":"d1e16135"},"_":"CRediT authorship contribution statement"}]},{"#name":"entry","$":{"depth":"1","id":"coi1","type":"conflict-of-interest"},"$$":[{"#name":"title","$":{"id":"d1e16157"},"_":"Declaration of competing interest"}]},{"#name":"entry","$":{"depth":"1","id":"d1e16161","type":"acknowledgment"},"$$":[{"#name":"title","$":{"id":"d1e16162"},"_":"Acknowledgments"}]},{"#name":"entry","$":{"depth":"1","id":"appSB","type":"appendices"},"$$":[{"#name":"label","_":"Appendix A"},{"#name":"title","$":{"id":"d1e16200"},"_":"Supplementary data"}]},{"#name":"entry","$":{"depth":"1","id":"da1","type":"data-availability"},"$$":[{"#name":"title","$":{"id":"aep-das-001"},"_":"Data availability"}]},{"#name":"entry","$":{"depth":"1","id":"bib1","type":"bibliography"},"$$":[{"#name":"title","$":{"id":"d1e16214"},"_":"References"}]}],"figures":[],"tables":[{"#name":"entry","$":{"id":"tbl1","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 1"},{"#name":"caption","$":{"truncated":"false"},"_":"Demographic information of studied subjects from two datasets. Age is reported as mean ± standard deviation. M/F: Male/Female."}]},{"#name":"entry","$":{"id":"tbl2","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 2"},{"#name":"caption","$":{"truncated":"true"},"_":"Details of fully connected layers in the Graph Transformer. Xi, Ei, Yi (i=1,2): The ith fully connected operation performed on the node features, edge features, and global features in the input and ou..."}]},{"#name":"entry","$":{"id":"tbl3","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 3"},{"#name":"caption","$":{"truncated":"true"},"_":"Results of MDD vs. HC classification experiments on the REST-MDD dataset using twelve methods (shown as mean±standard deviation), highlighting the best results in bold. The notation “S→T” indicates th..."}]},{"#name":"entry","$":{"id":"tbl4","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 4"},{"#name":"caption","$":{"truncated":"true"},"_":"Results of ASD vs. HC classification experiments on the ABIDE dataset using twelve methods (shown as mean±standard deviation), highlighting the best results in bold. The notation “S→T” indicates that ..."}]},{"#name":"entry","$":{"id":"tbl5","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 5"},{"#name":"caption","$":{"truncated":"false"},"_":"Influence of different trade-off parameters on GCDA for classifying MDD vs. HC on REST-MDD (i.e., Site 20 →Site 1), highlighting the best results in bold."}]},{"#name":"entry","$":{"id":"tbl6","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 6"},{"#name":"caption","$":{"truncated":"false"},"_":"Performance of GCDA and GCDA-G in MDD vs. HC classification on REST-MDD (i.e., Site 20 →Site 1), highlighting the best results in bold."}]},{"#name":"entry","$":{"id":"tbl7","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 7"},{"#name":"caption","$":{"truncated":"false"},"_":"Performance of GCDA and four recent state-of-the-art fMRI analysis methods in MDD vs. HC classification on the REST-MDD dataset (i.e., Site 20 →Site 1), with best results shown in bold."}]},{"#name":"entry","$":{"id":"tbl8","local-type":"table","type":"sections"},"$$":[{"#name":"label","_":"Table 8"},{"#name":"caption","$":{"truncated":"false"},"_":"Performance of GGM, No Pre-train, and GCDA in MDD vs. HC classification on the REST-MDD dataset."}]}],"extras":[],"attachments":[],"showEntitledTocLinks":false},"tail":{},"transientError":{"isOpen":false},"sidePanel":{"openState":1},"viewConfig":{"articleFeature":{"rightsAndContentLink":true,"sdAnswersButton":false},"pathPrefix":""},"virtualSpecialIssue":{"showVirtualSpecialIssueLink":false},"usageProps":{"itemStage":"S250","isAip":false,"tombAip":"0","sample":false},"userCookiePreferences":{"STRICTLY_NECESSARY":true,"PERFORMANCE":true,"FUNCTIONAL":true,"TARGETING":true}};
      </script>
      <noscript>
      JavaScript is disabled on your browser.
      Please enable JavaScript to use all the features on this page.
      <img src=https://smetrics.elsevier.com/b/ss/elsevier-sd-prod/1/G.4--NS/1739780257363?pageName=sd%3Aproduct%3Ajournal%3Aarticle&c16=els%3Arp%3Ast&c2=sd&v185=img&v33=ae%3AANON_GUEST&c1=ae%3A228598&c12=ae%3A12975512 />
    </noscript>
      <div id="elementForFocusReset" tabindex="-1"></div><a class="anchor sr-only sr-only-focusable u-display-inline anchor-primary" href="#screen-reader-main-content"><span class="anchor-text-container"><span class="anchor-text">Skip to main content</span></span></a><a class="anchor sr-only sr-only-focusable u-display-inline anchor-primary" href="#screen-reader-main-title"><span class="anchor-text-container"><span class="anchor-text">Skip to article</span></span></a>
      <div id="root"><div class="App" id="app" data-aa-name="root"><div class="page"><div class="sd-flex-container"><div class="sd-flex-content"><header id="gh-cnt"><div id="gh-main-cnt" class="u-flex-center-ver u-position-relative u-padding-s-hor u-padding-l-hor-from-xl"><a id="gh-branding" class="u-flex-center-ver" href="/" aria-label="ScienceDirect home page" data-aa-region="header" data-aa-name="ScienceDirect"><img class="gh-logo" src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/24/images/elsevier-non-solus-new-grey.svg" alt="Elsevier logo" height="48" width="54"/><svg xmlns="http://www.w3.org/2000/svg" version="1.1" height="15" viewBox="0 0 190 23" role="img" class="gh-wordmark u-margin-s-left" aria-labelledby="gh-wm-science-direct" focusable="false" aria-hidden="true" alt="ScienceDirect Wordmark"><title id="gh-wm-science-direct">ScienceDirect</title><g><path fill="#EB6500" d="M3.81 6.9c0-1.48 0.86-3.04 3.7-3.04 1.42 0 3.1 0.43 4.65 1.32l0.13-2.64c-1.42-0.63-2.97-0.96-4.78-0.96 -4.62 0-6.6 2.44-6.6 5.45 0 5.61 8.78 6.14 8.78 9.93 0 1.48-1.15 3.04-3.86 3.04 -1.72 0-3.4-0.56-4.72-1.39l-0.36 2.64c1.55 0.76 3.57 1.06 5.15 1.06 4.26 0 6.7-2.48 6.7-5.51C12.59 11.49 3.81 10.76 3.81 6.9M20.27 9.01c0.23-0.13 0.69-0.26 1.72-0.26 1.72 0 2.41 0.3 2.41 1.58h2.38c0-0.36 0-0.79-0.03-1.09 -0.23-1.98-2.15-2.67-4.88-2.67 -3 0-6.7 2.31-6.7 7.76 0 5.22 2.77 7.99 6.63 7.99 1.68 0 3.47-0.36 4.95-1.39l-0.2-2.31c-0.99 0.82-2.84 1.52-4.06 1.52 -2.14 0-4.55-1.71-4.55-5.91C17.93 10.2 20.01 9.18 20.27 9.01"></path><rect x="29.42" y="6.97" fill="#EB6500" width="2.54" height="14.95"></rect><path fill="#EB6500" d="M30.67 0.7c-0.92 0-1.65 0.92-1.65 1.81 0 0.93 0.76 1.85 1.65 1.85 0.89 0 1.68-0.96 1.68-1.88C32.35 1.55 31.56 0.7 30.67 0.7M48.06 14.13c0-5.18-1.42-7.56-6.01-7.56 -3.86 0-6.67 2.77-6.67 7.92 0 4.92 2.97 7.82 6.73 7.82 2.81 0 4.36-0.63 5.68-1.42l-0.2-2.31c-0.89 0.79-2.94 1.55-4.69 1.55 -3.14 0-4.88-1.95-4.88-5.51v-0.49H48.06M39.91 9.18c0.17-0.17 1.29-0.46 1.98-0.46 2.48 0 3.76 0.53 3.86 3.43h-7.46C38.56 10.27 39.71 9.37 39.91 9.18zM58.82 6.57c-2.24 0-3.63 1.12-4.85 2.61l-0.4-2.21h-2.34l0.13 1.19c0.1 0.76 0.13 1.78 0.13 2.97v10.79h2.54V11.88c0.69-0.96 2.15-2.48 2.48-2.64 0.23-0.13 1.29-0.4 2.08-0.4 2.28 0 2.48 1.15 2.54 3.43 0.03 1.19 0.03 3.17 0.03 3.17 0.03 3-0.1 6.47-0.1 6.47h2.54c0 0 0.07-4.49 0.07-6.96 0-1.48 0.03-2.97-0.1-4.46C63.31 7.43 61.49 6.57 58.82 6.57M72.12 9.01c0.23-0.13 0.69-0.26 1.72-0.26 1.72 0 2.41 0.3 2.41 1.58h2.38c0-0.36 0-0.79-0.03-1.09 -0.23-1.98-2.15-2.67-4.88-2.67 -3 0-6.7 2.31-6.7 7.76 0 5.22 2.77 7.99 6.63 7.99 1.68 0 3.47-0.36 4.95-1.39l-0.2-2.31c-0.99 0.82-2.84 1.52-4.06 1.52 -2.15 0-4.55-1.71-4.55-5.91C69.77 10.2 71.85 9.18 72.12 9.01M92.74 14.13c0-5.18-1.42-7.56-6.01-7.56 -3.86 0-6.67 2.77-6.67 7.92 0 4.92 2.97 7.82 6.73 7.82 2.81 0 4.36-0.63 5.68-1.42l-0.2-2.31c-0.89 0.79-2.94 1.55-4.69 1.55 -3.14 0-4.88-1.95-4.88-5.51v-0.49H92.74M84.59 9.18c0.17-0.17 1.29-0.46 1.98-0.46 2.48 0 3.76 0.53 3.86 3.43h-7.46C83.24 10.27 84.39 9.37 84.59 9.18zM103.9 1.98h-7.13v19.93h6.83c7.26 0 9.77-5.68 9.77-10.03C113.37 7.33 110.93 1.98 103.9 1.98M103.14 19.8h-3.76V4.1h4.09c5.38 0 6.96 4.39 6.96 7.79C110.43 16.87 108.19 19.8 103.14 19.8zM118.38 0.7c-0.92 0-1.65 0.92-1.65 1.81 0 0.93 0.76 1.85 1.65 1.85 0.89 0 1.69-0.96 1.69-1.88C120.07 1.55 119.28 0.7 118.38 0.7"></path><rect x="117.13" y="6.97" fill="#EB6500" width="2.54" height="14.95"></rect><path fill="#EB6500" d="M130.2 6.6c-1.62 0-2.87 1.45-3.4 2.74l-0.43-2.37h-2.34l0.13 1.19c0.1 0.76 0.13 1.75 0.13 2.9v10.86h2.54v-9.51c0.53-1.29 1.72-3.7 3.17-3.7 0.96 0 1.06 0.99 1.06 1.22l2.08-0.6V9.18c0-0.03-0.03-0.17-0.06-0.4C132.8 7.36 131.91 6.6 130.2 6.6M145.87 14.13c0-5.18-1.42-7.56-6.01-7.56 -3.86 0-6.67 2.77-6.67 7.92 0 4.92 2.97 7.82 6.73 7.82 2.81 0 4.36-0.63 5.68-1.42l-0.2-2.31c-0.89 0.79-2.94 1.55-4.69 1.55 -3.14 0-4.89-1.95-4.89-5.51v-0.49H145.87M137.72 9.18c0.17-0.17 1.29-0.46 1.98-0.46 2.48 0 3.76 0.53 3.86 3.43h-7.46C136.37 10.27 137.52 9.37 137.72 9.18zM153.23 9.01c0.23-0.13 0.69-0.26 1.72-0.26 1.72 0 2.41 0.3 2.41 1.58h2.38c0-0.36 0-0.79-0.03-1.09 -0.23-1.98-2.14-2.67-4.88-2.67 -3 0-6.7 2.31-6.7 7.76 0 5.22 2.77 7.99 6.63 7.99 1.69 0 3.47-0.36 4.95-1.39l-0.2-2.31c-0.99 0.82-2.84 1.52-4.06 1.52 -2.15 0-4.55-1.71-4.55-5.91C150.89 10.2 152.97 9.18 153.23 9.01M170 19.44c-0.92 0.36-1.72 0.69-2.51 0.69 -1.16 0-1.58-0.66-1.58-2.34V8.95h3.93V6.97h-3.93V2.97h-2.48v3.99h-2.71v1.98h2.71v9.67c0 2.64 1.39 3.73 3.33 3.73 1.15 0 2.54-0.39 3.43-0.79L170 19.44M173.68 5.96c-1.09 0-2-0.87-2-1.97 0-1.1 0.91-1.97 2-1.97s1.98 0.88 1.98 1.98C175.66 5.09 174.77 5.96 173.68 5.96zM173.67 2.46c-0.85 0-1.54 0.67-1.54 1.52 0 0.85 0.69 1.54 1.54 1.54 0.85 0 1.54-0.69 1.54-1.54C175.21 3.13 174.52 2.46 173.67 2.46zM174.17 5.05c-0.09-0.09-0.17-0.19-0.25-0.3l-0.41-0.56h-0.16v0.87h-0.39V2.92c0.22-0.01 0.47-0.03 0.66-0.03 0.41 0 0.82 0.16 0.82 0.64 0 0.29-0.21 0.55-0.49 0.63 0.23 0.32 0.45 0.62 0.73 0.91H174.17zM173.56 3.22l-0.22 0.01v0.63h0.22c0.26 0 0.43-0.05 0.43-0.34C174 3.28 173.83 3.21 173.56 3.22z"></path></g></svg></a><div class="gh-nav-cnt u-hide-from-print"><div class="gh-nav-links-container gh-nav-links-container-h u-hide-from-print gh-nav-content-container"><nav aria-label="links" class="gh-nav gh-nav-links gh-nav-h"><ul class="gh-nav-list u-list-reset"><li class="gh-nav-item gh-move-to-spine"><a class="anchor gh-nav-action text-s anchor-secondary anchor-medium" href="/browse/journals-and-books" id="gh-journals-books-link" data-aa-region="header" data-aa-name="Journals &amp; Books"><span class="anchor-text-container"><span class="anchor-text">Journals &amp; Books</span></span></a></li></ul></nav><nav aria-label="utilities" class="gh-nav gh-nav-utilities gh-nav-h"><ul class="gh-nav-list u-list-reset"><li class="gh-nav-help text-s u-flex-center-ver u-gap-6 gh-nav-action"><div class="gh-move-to-spine gh-help-button gh-help-icon gh-nav-item"><div class="popover" id="gh-help-icon-popover"><div id="popover-trigger-gh-help-icon-popover"><input type="hidden"/><button class="button-link button-link-secondary gh-icon-btn button-link-medium button-link-icon-left" type="button" aria-expanded="false"><svg focusable="false" viewBox="0 0 114 128" height="20" width="20" class="icon icon-help gh-icon"><path d="M57 8C35.69 7.69 15.11 21.17 6.68 40.71c-8.81 19.38-4.91 43.67 9.63 59.25 13.81 15.59 36.85 21.93 56.71 15.68 21.49-6.26 37.84-26.81 38.88-49.21 1.59-21.15-10.47-42.41-29.29-52.1C74.76 10.17 65.88 7.99 57 8zm0 10c20.38-.37 39.57 14.94 43.85 34.85 4.59 18.53-4.25 39.23-20.76 48.79-17.05 10.59-40.96 7.62-54.9-6.83-14.45-13.94-17.42-37.85-6.83-54.9C26.28 26.5 41.39 17.83 57 18zm-.14 14C45.31 32.26 40 40.43 40 50v2h10v-2c0-4.22 2.22-9.66 8-9.24 5.5.4 6.32 5.14 5.78 8.14C62.68 55.06 52 58.4 52 69.4V76h10v-5.56c0-8.16 11.22-11.52 12-21.7.74-9.86-5.56-16.52-16-16.74-.39-.01-.76-.01-1.14 0zM52 82v10h10V82H52z"></path></svg><span class="button-link-text-container"><span class="button-link-text">Help</span></span></button></div></div></div></li><li class="gh-nav-search text-s u-flex-center-ver u-gap-6 gh-nav-action"><div class="gh-search-toggle gh-nav-item search-button-link"><a class="anchor button-link-secondary anchor-secondary u-margin-l-left gh-nav-action gh-icon-btn anchor-medium anchor-icon-left anchor-with-icon" href="/search" id="gh-search-link" data-aa-button="search-in-header-opened-from-article" role="button"><svg focusable="false" viewBox="0 0 100 128" height="20" class="icon icon-search gh-icon"><path d="M19.22 76.91c-5.84-5.84-9.05-13.6-9.05-21.85s3.21-16.01 9.05-21.85c5.84-5.83 13.59-9.05 21.85-9.05 8.25 0 16.01 3.22 21.84 9.05 5.84 5.84 9.05 13.6 9.05 21.85s-3.21 16.01-9.05 21.85c-5.83 5.83-13.59 9.05-21.84 9.05-8.26 0-16.01-3.22-21.85-9.05zm80.33 29.6L73.23 80.19c5.61-7.15 8.68-15.9 8.68-25.13 0-10.91-4.25-21.17-11.96-28.88-7.72-7.71-17.97-11.96-28.88-11.96S19.9 18.47 12.19 26.18C4.47 33.89.22 44.15.22 55.06s4.25 21.17 11.97 28.88C19.9 91.65 30.16 95.9 41.07 95.9c9.23 0 17.98-3.07 25.13-8.68l26.32 26.32 7.03-7.03"></path></svg><span class="anchor-text-container"><span class="anchor-text">Search</span></span></a></div></li></ul></nav></div></div><div class="gh-profile-container gh-move-to-spine u-hide-from-print"><a class="anchor text-s u-clr-grey8 u-margin-l-left gh-icon-btn anchor-primary anchor-medium anchor-icon-left anchor-with-icon" href="/user/login?targetURL=%2Fscience%2Farticle%2Fpii%2FS1361841524003281&amp;from=globalheader" id="gh-myaccount-btn" data-aa-region="header" data-aa-name="personalsignin"><svg focusable="false" viewBox="0 0 106 128" height="20" aria-hidden="true" class="icon icon-person gh-cta-btn-icon"><path d="M11.07 120l.84-9.29C13.88 91.92 35.25 87.78 53 87.78c17.74 0 39.11 4.13 41.08 22.84l.84 9.38h10.04l-.93-10.34C101.88 89.23 83.89 78 53 78S4.11 89.22 1.95 109.73L1.04 120h10.03M53 17.71c-9.72 0-18.24 8.69-18.24 18.59 0 13.67 7.84 23.98 18.24 23.98S71.24 49.97 71.24 36.3c0-9.9-8.52-18.59-18.24-18.59zM53 70c-15.96 0-28-14.48-28-33.67C25 20.97 37.82 8 53 8s28 12.97 28 28.33C81 55.52 68.96 70 53 70"></path></svg><span class="anchor-text-container"><span class="anchor-text">My account</span></span></a></div><a class="anchor text-s u-clr-grey8 gh-move-to-spine u-hide-from-print u-margin-l-left anchor-secondary gh-icon-btn anchor-medium anchor-icon-left anchor-with-icon" href="/user/institution/login?targetURL=%2Fscience%2Farticle%2Fpii%2FS1361841524003281" id="gh-institutionalsignin-btn" data-aa-region="header" data-aa-name="institutionalsignin"><svg focusable="false" viewBox="0 0 106 128" height="20" aria-hidden="true" class="icon icon-institution gh-cta-btn-icon"><path d="M84 98h10v10H12V98h10V52h14v46h10V52h14v46h10V52h14v46zM12 36.86l41-20.84 41 20.84V42H12v-5.14zM104 52V30.74L53 4.8 2 30.74V52h10v36H2v30h102V88H94V52h10z"></path></svg><span class="anchor-text-container"><span class="anchor-text">Sign in</span></span></a><div id="gh-mobile-menu" class="mobile-menu u-hide-from-print"><div class="gh-hamburger u-fill-grey7"><button class="button-link u-flex-center-ver button-link-primary button-link-icon-left" type="button" aria-label="Toggle mobile menu" aria-expanded="false"><svg class="gh-hamburger-svg-el gh-hamburger-closed" role="img" aria-hidden="true" height="20" width="20"><path d="M0 14h40v2H0zm0-7h40v2H0zm0-7h40v2H0z"></path></svg></button></div><div id="gh-overlay" class="mobile-menu-overlay u-overlay u-display-none" role="button" tabindex="-1"></div><div id="gh-drawer" aria-label="Mobile menu" class="" role="navigation"></div></div></div></header><div class="Article Preview" id="mathjax-container" role="main"><div class="accessbar-sticky"><div id="screen-reader-main-content"></div><div role="region" aria-label="Download options and search"><div class="accessbar"><div class="accessbar-label"></div><ul aria-label="PDF Options"><li class="accessbar-item-show-from-initial accessbar-item-show-from-xs accessbar-item-show-from-md RemoteAccess"><a class="link-button RemoteAccessButton accessbar-utility-component accessbar-utility-link link-button-primary link-button-icon-left" href="/user/institution/login?targetUrl=%2Fscience%2Farticle%2Fpii%2FS1361841524003281" aria-label="Access through your organization"><svg focusable="false" viewBox="0 0 106 128" height="20" aria-label="Seamless access" role="img" class="icon icon-institution"><path d="M84 98h10v10H12V98h10V52h14v46h10V52h14v46h10V52h14v46zM12 36.86l41-20.84 41 20.84V42H12v-5.14zM104 52V30.74L53 4.8 2 30.74V52h10v36H2v30h102V88H94V52h10z"></path></svg><span class="link-button-text-container"><span class="link-button-text"><span>Access through&nbsp;<strong>your organization</strong></span></span></span></a></li><li class="accessbar-item-hide-from-initial accessbar-item-hide-from-xs accessbar-item-show-from-md PurchasePDF"><a class="anchor accessbar-utility-component accessbar-utility-link anchor-primary" href="/getaccess/pii/S1361841524003281/purchase" target="_blank" aria-label="Purchase PDF" rel="noreferrer noopener"><span class="anchor-text-container"><span class="anchor-text"><span>Purchase PDF</span></span></span></a></li><li class="accessbar-item-hide-from-initial accessbar-item-hide-from-xs accessbar-item-show-from-md Divider"><span class="accessbar-divider"></span></li><li class="accessbar-item-hide-from-initial accessbar-item-hide-from-xs accessbar-item-show-from-md PatientAccess"><a class="anchor accessbar-utility-component accessbar-utility-link anchor-primary" href="https://www.elsevier.com/open-science/science-and-society/access-for-healthcare-and-patients" target="_blank" aria-label="Patient Access" rel="noreferrer noopener"><span class="anchor-text-container"><span class="anchor-text"><span>Patient Access</span></span></span></a></li><li class="accessbar-item-show-from-initial accessbar-item-show-from-xs accessbar-item-hide-from-md OverflowPopover"><div class="popover accessbar-overflow-popover" id="OverflowPopoverAnchor"><div id="popover-trigger-OverflowPopoverAnchor"><button class="button-link accessbar-utility-component button-link-primary button-link-icon-right" type="button" aria-label="Other access options"><span class="button-link-text-container"><span class="button-link-text"><span>Other access options</span></span></span><svg focusable="false" viewBox="0 0 92 128" height="20" class="icon icon-navigate-down"><path d="M1 51l7-7 38 38 38-38 7 7-45 45z"></path></svg></button></div></div></li></ul><form class="QuickSearch" action="/search#submit" method="get" aria-label="form"><div class="search-input"><div class="search-input-container search-input-container-no-label"><label class="search-input-label u-hide-visually" for="article-quick-search">Search ScienceDirect</label><input type="search" id="article-quick-search" name="qs" class="search-input-field" aria-describedby="article-quick-search-description-message" aria-invalid="false" aria-label="Search ScienceDirect" placeholder="Search ScienceDirect" value=""/></div><div class="search-input-message-container"><div class="search-input-validation-error" aria-live="polite"></div><div id="article-quick-search-description-message"></div></div></div><button type="submit" class="button u-margin-xs-left button-primary small button-icon-only" aria-disabled="false" aria-label="Submit search"><svg focusable="false" viewBox="0 0 100 128" height="20" class="icon icon-search"><path d="M19.22 76.91c-5.84-5.84-9.05-13.6-9.05-21.85s3.21-16.01 9.05-21.85c5.84-5.83 13.59-9.05 21.85-9.05 8.25 0 16.01 3.22 21.84 9.05 5.84 5.84 9.05 13.6 9.05 21.85s-3.21 16.01-9.05 21.85c-5.83 5.83-13.59 9.05-21.84 9.05-8.26 0-16.01-3.22-21.85-9.05zm80.33 29.6L73.23 80.19c5.61-7.15 8.68-15.9 8.68-25.13 0-10.91-4.25-21.17-11.96-28.88-7.72-7.71-17.97-11.96-28.88-11.96S19.9 18.47 12.19 26.18C4.47 33.89.22 44.15.22 55.06s4.25 21.17 11.97 28.88C19.9 91.65 30.16 95.9 41.07 95.9c9.23 0 17.98-3.07 25.13-8.68l26.32 26.32 7.03-7.03"></path></svg></button><input type="hidden" name="origin" value="article"/><input type="hidden" name="zone" value="qSearch"/></form></div></div></div><div class="article-wrapper u-padding-s-top grid row"><div role="navigation" aria-label="Table of Contents" class="preview-sidebar u-display-block-from-lg col-lg-6"><div class="PreviewTableOfContents"><h2 class="u-h4 preview-table-of-contents-title">Article preview</h2><ul class="preview-table-of-contents-list"><li id="preview-section-abstract-item" class=""><a class="anchor anchor-primary" href="#preview-section-abstract"><span class="anchor-text-container"><span class="anchor-text">Abstract</span></span></a></li><li id="preview-section-introduction-item" class=""><a class="anchor anchor-primary" href="#preview-section-introduction"><span class="anchor-text-container"><span class="anchor-text">Introduction</span></span></a></li><li id="preview-section-snippets-item" class=""><a class="anchor anchor-primary" href="#preview-section-snippets"><span class="anchor-text-container"><span class="anchor-text">Section snippets</span></span></a></li><li id="preview-section-references-item" class=""><a class="anchor anchor-primary" href="#preview-section-references"><span class="anchor-text-container"><span class="anchor-text">References (70)</span></span></a></li></ul></div></div><article class="col-lg-12 col-md-16 pad-left pad-right" lang="en"><div class="Publication" id="publication"><div class="publication-brand u-display-block-from-sm"><a class="anchor u-display-flex anchor-primary" href="/journal/medical-image-analysis" title="Go to Medical Image Analysis on ScienceDirect"><span class="anchor-text-container"><span class="anchor-text"><img class="publication-brand-image" src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1/image/elsevier-non-solus.png" alt="Elsevier"/></span></span></a></div><div class="publication-volume u-text-center"><h2 class="publication-title u-h3" id="publication-title"><a class="anchor anchor-secondary publication-title-link" href="/journal/medical-image-analysis" title="Go to Medical Image Analysis on ScienceDirect"><span class="anchor-text-container"><span class="anchor-text">Medical Image Analysis</span></span></a></h2><div class="text-xs"><a class="anchor anchor-primary" href="/journal/medical-image-analysis/vol/101/suppl/C" title="Go to table of contents for this volume/issue"><span class="anchor-text-container"><span class="anchor-text">Volume 101</span></span></a>, <!-- -->April 2025<!-- -->, 103403</div></div><div class="publication-cover u-display-block-from-sm"><a class="anchor u-display-flex anchor-primary" href="/journal/medical-image-analysis/vol/101/suppl/C"><span class="anchor-text-container"><span class="anchor-text"><img class="publication-cover-image" src="https://ars.els-cdn.com/content/image/1-s2.0-S1361841524X00080-cov150h.gif" alt="Medical Image Analysis"/></span></span></a></div></div><div class="PageDivider"></div><h1 id="screen-reader-main-title" class="Head u-font-serif u-h2 u-margin-s-ver"><span class="title-text">Self-supervised graph contrastive learning with diffusion augmentation for functional MRI analysis and brain disorder detection</span></h1><div class="Banner" id="banner"><div class="wrapper truncated"><div aria-live="polite"></div><div class="AuthorGroups"><div class="author-group" id="author-group"><span class="sr-only">Author links open overlay panel</span><button class="button-link button-link-secondary button-link-underline" type="button" data-sd-ui-side-panel-opener="true" data-xocs-content-type="author" data-xocs-content-id="au000001"><span class="button-link-text-container"><span class="button-link-text"><span class="react-xocs-alternative-link"><span class="given-name">Xiaochuan</span> <span class="text surname">Wang</span> </span><span class="author-ref" id="baff1"><sup>a</sup></span></span></span></button>, <button class="button-link button-link-secondary button-link-underline" type="button" data-sd-ui-side-panel-opener="true" data-xocs-content-type="author" data-xocs-content-id="au000002"><span class="button-link-text-container"><span class="button-link-text"><span class="react-xocs-alternative-link"><span class="given-name">Yuqi</span> <span class="text surname">Fang</span> </span><span class="author-ref" id="baff1"><sup>a</sup></span></span></span></button>, <button class="button-link button-link-secondary button-link-underline" type="button" data-sd-ui-side-panel-opener="true" data-xocs-content-type="author" data-xocs-content-id="au000003"><span class="button-link-text-container"><span class="button-link-text"><span class="react-xocs-alternative-link"><span class="given-name">Qianqian</span> <span class="text surname">Wang</span> </span><span class="author-ref" id="baff1"><sup>a</sup></span></span></span></button>, <button class="button-link button-link-secondary button-link-underline" type="button" data-sd-ui-side-panel-opener="true" data-xocs-content-type="author" data-xocs-content-id="au000004"><span class="button-link-text-container"><span class="button-link-text"><span class="react-xocs-alternative-link"><span class="given-name">Pew-Thian</span> <span class="text surname">Yap</span> </span><span class="author-ref" id="baff1"><sup>a</sup></span></span></span></button>, <button class="button-link button-link-secondary button-link-underline" type="button" data-sd-ui-side-panel-opener="true" data-xocs-content-type="author" data-xocs-content-id="au000005"><span class="button-link-text-container"><span class="button-link-text"><span class="react-xocs-alternative-link"><span class="given-name">Hongtu</span> <span class="text surname">Zhu</span> </span><span class="author-ref" id="baff2"><sup>b</sup></span></span></span></button>, <button class="button-link button-link-secondary button-link-underline" type="button" data-sd-ui-side-panel-opener="true" data-xocs-content-type="author" data-xocs-content-id="au000006"><span class="button-link-text-container"><span class="button-link-text"><span class="react-xocs-alternative-link"><span class="given-name">Mingxia</span> <span class="text surname">Liu</span> </span><span class="author-ref" id="baff1"><sup>a</sup></span><svg focusable="false" viewBox="0 0 106 128" height="20" title="Correspondence author icon" class="icon icon-person react-xocs-author-icon u-fill-grey8"><path d="M11.07 120l.84-9.29C13.88 91.92 35.25 87.78 53 87.78c17.74 0 39.11 4.13 41.08 22.84l.84 9.38h10.04l-.93-10.34C101.88 89.23 83.89 78 53 78S4.11 89.22 1.95 109.73L1.04 120h10.03M53 17.71c-9.72 0-18.24 8.69-18.24 18.59 0 13.67 7.84 23.98 18.24 23.98S71.24 49.97 71.24 36.3c0-9.9-8.52-18.59-18.24-18.59zM53 70c-15.96 0-28-14.48-28-33.67C25 20.97 37.82 8 53 8s28 12.97 28 28.33C81 55.52 68.96 70 53 70"></path></svg><svg focusable="false" viewBox="0 0 102 128" height="20" title="Author email or social media contact details icon" class="icon icon-envelope react-xocs-author-icon u-fill-grey8"><path d="M55.8 57.2c-1.78 1.31-5.14 1.31-6.9 0L17.58 34h69.54L55.8 57.19zM0 32.42l42.94 32.62c2.64 1.95 6.02 2.93 9.4 2.93s6.78-.98 9.42-2.93L102 34.34V24H0zM92 88.9L73.94 66.16l-8.04 5.95L83.28 94H18.74l18.38-23.12-8.04-5.96L10 88.94V51.36L0 42.9V104h102V44.82l-10 8.46V88.9"></path></svg></span></span></button></div></div></div><button class="button-link u-margin-s-ver button-link-primary button-link-icon-right" type="button" id="show-more-btn" data-aa-button="icon-expand"><span class="button-link-text-container"><span class="button-link-text">Show more</span></span><svg focusable="false" viewBox="0 0 92 128" height="20" class="icon icon-navigate-down"><path d="M1 51l7-7 38 38 38-38 7 7-45 45z"></path></svg></button><div class="banner-options u-padding-xs-bottom"><button class="button-link AddToMendeley button-link-secondary u-margin-s-right u-display-inline-flex-from-md button-link-icon-left button-link-has-colored-icon" type="button"><svg focusable="false" viewBox="0 0 86 128" height="20" class="icon icon-plus"><path d="M48 58V20H38v38H0v10h38v38h10V68h38V58z"></path></svg><span class="button-link-text-container"><span class="button-link-text">Add to Mendeley</span></span></button><div class="Social u-display-inline-block" id="social"><div class="popover social-popover" id="social-popover"><div id="popover-trigger-social-popover"><button class="button-link button-link-secondary u-margin-s-right button-link-icon-left button-link-has-colored-icon" type="button" aria-expanded="false" aria-haspopup="true"><svg focusable="false" viewBox="0 0 114 128" height="20" class="icon icon-share"><path d="M90 112c-6.62 0-12-5.38-12-12s5.38-12 12-12 12 5.38 12 12-5.38 12-12 12zM24 76c-6.62 0-12-5.38-12-12s5.38-12 12-12 12 5.38 12 12-5.38 12-12 12zm66-60c6.62 0 12 5.38 12 12s-5.38 12-12 12-12-5.38-12-12 5.38-12 12-12zm0 62c-6.56 0-12.44 2.9-16.48 7.48L45.1 70.2c.58-1.98.9-4.04.9-6.2s-.32-4.22-.9-6.2l28.42-15.28C77.56 47.1 83.44 50 90 50c12.14 0 22-9.86 22-22S102.14 6 90 6s-22 9.86-22 22c0 1.98.28 3.9.78 5.72L40.14 49.1C36.12 44.76 30.38 42 24 42 11.86 42 2 51.86 2 64s9.86 22 22 22c6.38 0 12.12-2.76 16.14-7.12l28.64 15.38c-.5 1.84-.78 3.76-.78 5.74 0 12.14 9.86 22 22 22s22-9.86 22-22-9.86-22-22-22z"></path></svg><span class="button-link-text-container"><span class="button-link-text">Share</span></span></button></div></div></div><div class="ExportCitation u-display-inline-block" id="export-citation"><div class="popover export-citation-popover" id="export-citation-popover"><div id="popover-trigger-export-citation-popover"><button class="button-link button-link-secondary button-link-icon-left button-link-has-colored-icon" type="button" aria-expanded="false" aria-haspopup="true"><svg focusable="false" viewBox="0 0 104 128" height="20" class="icon icon-cited-by-66"><path d="M2 58.78V106h44V64H12v-5.22C12 40.28 29.08 32 46 32V22C20.1 22 2 37.12 2 58.78zM102 32V22c-25.9 0-44 15.12-44 36.78V106h44V64H68v-5.22C68 40.28 85.08 32 102 32z"></path></svg><span class="button-link-text-container"><span class="button-link-text">Cite</span></span></button></div></div></div></div></div><div class="ArticleIdentifierLinks u-margin-xs-bottom text-xs" id="article-identifier-links"><a class="anchor doi anchor-primary" href="https://doi.org/10.1016/j.media.2024.103403" target="_blank" rel="noreferrer noopener" aria-label="Persistent link using digital object identifier" title="Persistent link using digital object identifier"><span class="anchor-text-container"><span class="anchor-text">https://doi.org/10.1016/j.media.2024.103403</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a><a class="anchor rights-and-content anchor-primary" href="https://s100.copyright.com/AppDispatchServlet?publisherName=ELS&amp;contentID=S1361841524003281&amp;orderBeanReset=true" target="_blank" rel="noreferrer noopener"><span class="anchor-text-container"><span class="anchor-text">Get rights and content</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></div><section class="ReferencedArticles"></section><section class="ReferencedArticles"></section><div id="preview-section-abstract"><div class="PageDivider"></div><div class="Abstracts u-font-serif" id="abstracts"><div class="abstract author-highlights" id="d1e9177"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Highlights</h2><div id="d1e9180"><div class="u-margin-s-bottom" id="d1e9181"><ul class="list"><li class="react-xocs-list-item"><span class="list-label">•</span><span><div class="u-margin-s-bottom" id="d1e9187">Creating a self-supervised graph contrastive learning framework for fMRI analysis and brain disease detection to alleviate the small-sample-size problem.</div></span></li><li class="react-xocs-list-item"><span class="list-label">•</span><span><div class="u-margin-s-bottom" id="d1e9192">Designing a graph diffusion augmentation strategy to preserve the integrity of original BOLD signals.</div></span></li><li class="react-xocs-list-item"><span class="list-label">•</span><span><div class="u-margin-s-bottom" id="d1e9197">Conducting extensive experiments on two rs-fMRI datasets with 1,230 subjects.</div></span></li></ul></div></div></div><div class="abstract author" id="d1e9156"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Abstract</h2><div id="d1e9159"><div class="u-margin-s-bottom" id="d1e9160">Resting-state functional magnetic resonance imaging (rs-fMRI) provides a non-invasive imaging technique to study patterns of brain activity, and is increasingly used to facilitate automated brain disorder analysis. Existing fMRI-based learning methods often rely on labeled data to construct learning models, while the data annotation process typically requires significant time and resource investment. Graph contrastive learning offers a promising solution to address the small labeled data issue, by augmenting fMRI time series for self-supervised learning. However, data augmentation strategies employed in these approaches may damage the original blood-oxygen-level-dependent (BOLD) signals, thus hindering subsequent fMRI feature extraction. In this paper, we propose a self-supervised graph contrastive learning framework with diffusion augmentation (GCDA) for functional MRI analysis. The GCDA consists of a <em>pretext model</em> and a <em>task-specific model</em>. In the pretext model, we first augment each brain functional connectivity network derived from fMRI through a graph diffusion augmentation (GDA) module, and then use two graph isomorphism networks with shared parameters to extract features in a self-supervised contrastive learning manner. The pretext model can be optimized without the need for labeled training data, while the GDA focuses on perturbing graph edges and nodes, thus preserving the integrity of original BOLD signals. The task-specific model involves fine-tuning the trained pretext model to adapt to downstream tasks. Experimental results on two rs-fMRI cohorts with a total of 1230 subjects demonstrate the effectiveness of our method compared with several state-of-the-arts.</div></div></div><div class="abstract graphical" id="d1e9168"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Graphical abstract</h2><div id="d1e9171"><div class="u-margin-s-bottom" id="d1e9172"><span class="display"><figure class="figure text-xs" id="dfig1"><span><img src="https://ars.els-cdn.com/content/image/1-s2.0-S1361841524003281-ga1.jpg" height="143" alt=""/><ol class="u-margin-s-bottom"><li><a class="anchor download-link u-font-sans anchor-primary" href="https://ars.els-cdn.com/content/image/1-s2.0-S1361841524003281-ga1_lrg.jpg" target="_blank" download="" title="Download high-res image (283KB)"><span class="anchor-text-container"><span class="anchor-text">Download: <span class="download-link-title">Download high-res image (283KB)</span></span></span></a></li><li><a class="anchor download-link u-font-sans anchor-primary" href="https://ars.els-cdn.com/content/image/1-s2.0-S1361841524003281-ga1.jpg" target="_blank" download="" title="Download full-size image"><span class="anchor-text-container"><span class="anchor-text">Download: <span class="download-link-title">Download full-size image</span></span></span></a></li></ol></span></figure></span></div></div></div></div></div><div id="preview-section-introduction"><div class="PageDivider"></div><div class="Introduction u-font-serif u-margin-l-ver"><h2 class="u-h4 u-margin-s-bottom">Introduction</h2><section id="sec1"><div class="u-margin-s-bottom" id="d1e9227">Resting-state functional magnetic resonance imaging (rs-fMRI) focuses on measuring low-frequency blood-oxygen-level-dependent (BOLD) signals during a resting state without performing specific tasks, and has become an essential tool in neuroimaging (Shirer et al., 2015, Amemiya et al., 2016). The functional connectivity (FC) described by rs-fMRI can capture brain activity patterns and relationships between brain regions-of-interest (ROIs), which is increasingly used to explore the pathological mechanisms and conduct automated diagnosis of brain diseases such as major depressive disorder (MDD) and autism spectrum disorder (ASD) (Dai et al., 2023, Nebel et al., 2022, Mao et al., 2019, Fang et al., 2023). With the advancement of machine learning and deep learning, an increasing number of technologies are being developed for fMRI biomarker discovery and automated brain disorder detection (Bondi et al., 2023, Hou et al., 2023, Hebling Vieira et al., 2021, Wang et al., 2024). However, learning models typically need substantial annotated samples to achieve good generalization performance (Ingalhalikar et al., 2021, Cui et al., 2023, Wang et al., 2023, Weiner et al., 2013).</div><div class="u-margin-s-bottom" id="d1e9250">Self-supervised learning such as graph contrastive learning offers a promising solution to this issue without the requirement for labeled data, leveraging its strong transferability to address the small-sample-size problem (Fedorov et al., 2024). Graph augmentation is generally a crucial component within graph contrastive learning frameworks (Demirel and Holz, 2024). Many fMRI-based contrastive learning studies focus on augmenting fMRI time series using various techniques (<em>e.g.</em>, window slicing and window warping), which may damage the information embedded in the original BOLD signals and thereby impede subsequent fMRI feature extraction (Wang et al., 2022, Tang et al., 2022, Bijsterbosch et al., 2017). Several state-of-the-art (SOTA) graph augmentation strategies, such as GNN-based methods used in Auto-GCL (Yin et al., 2022) and AD-GCL (Suresh et al., 2021), are still difficult to generate high-quality samples since their generators are not specifically tailored for graph generation. As a powerful deep generative model, diffusion models have seen extensive applications across diverse fields with unparalleled performance, including image synthesis, molecule design, and medical data analysis (Yang et al., 2023, Wu et al., 2024). However, a few studies investigate the diffusion model to implement data augmentation based on brain functional connectivity networks (FCNs) and integrate it with contrastive learning for brain disease detection.</div><div class="u-margin-s-bottom" id="d1e9287">In this paper, we propose a self-supervised graph contrastive learning framework with diffusion augmentation (GCDA) for fMRI analysis and brain disorder detection. The GCDA consists of a <em>pretext model</em> that learns general and transferable fMRI features and a <em>task-specific model</em> that aims to fine-tune the pretext model to cater to downstream tasks. Specifically, the pretext model contains three components: (1) a graph construction module, (2) a graph diffusion augmentation (GDA) module, and (3) a graph contrastive learning module. First, we utilize the graph construction module to build functional connectivity networks/graphs based on fMRI data. The graphs are then passed through the GDA module, which perturbs the edges and nodes of the graph, thus preserving the integrity of the original BOLD signal while being able to generate high-quality augmented graphs. Then, two graph isomorphism networks (GINs) with shared parameters are employed to extract general fMRI features in a self-supervised contrastive learning manner. Note that the pretext model is optimized based on unlabeled fMRI data, eliminating the tedious annotation procedure. The task-specific model is proposed to adjust the well-trained parameters of the pretext model to adapt to downstream tasks in a supervised task-oriented manner. We assess the proposed GCDA on two datasets with rs-fMRI data from a total of 1230 subjects, and the experimental results indicate that our GCDA surpasses several SOTA approaches in automatically diagnosing two types of brain diseases.</div><div class="u-margin-s-bottom" id="d1e9295">The main contributions of this work are outlined below.</div><div class="u-margin-s-bottom" id="d1e9297"><ul class="list"><li class="react-xocs-list-item"><span class="list-label">•</span><span><div class="u-margin-s-bottom" id="d1e9303">A self-supervised graph contrastive learning framework with diffusion augmentation is developed for fMRI analysis and brain disease detection, which effectively tackles the small-sample-size problem in fMRI studies.</div></span></li><li class="react-xocs-list-item"><span class="list-label">•</span><span><div class="u-margin-s-bottom" id="d1e9308">A novel graph diffusion augmentation strategy is designed to modify node and edge features within a brain graph, which greatly helps preserve the integrity of the original signals and facilitate effective fMRI feature extraction.</div></span></li><li class="react-xocs-list-item"><span class="list-label">•</span><span><div class="u-margin-s-bottom" id="d1e9313">Experiments on two rs-fMRI datasets suggest the superiority of our method compared to several state-of-the-art approaches in brain disease diagnosis. Moreover, our method aids in identifying functional connectivity abnormalities and brain regions associated with diseases, thus facilitating fMRI-based brain disease analysis in clinical practice.</div></span></li></ul></div><div class="u-margin-s-bottom" id="d1e9315">The remainder of this work is organized as follows. We review related studies in Section 2. In Section 3, we introduce studied materials and the proposed method. In Section 4, we present experimental settings and experimental results. In Section 5, we discuss several key components of the proposed method, as well as several limitations of the current work. Finally, we conclude this paper in Section 6.</div></section></div></div><div id="preview-section-snippets"><div class="PageDivider"></div><div class="Snippets u-font-serif"><h2 class="u-h4 u-margin-l-ver">Section snippets</h2><section><section id="sec2"><section id="sec2.1"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Self-supervised learning for fMRI analysis</h2><div class="u-margin-s-bottom" id="d1e9353">Self-supervised learning is a learning paradigm where the model uses the intrinsic structure or features within the data to generate labels or supervised signals. It then learns to extract meaningful information by using these generated labels as training targets (Liu et al., 2021). This learning paradigm does not require annotation and plays a crucial role in advancing fMRI analysis as well as brain disorder diagnosis. For instance, Wen et al. (2023) developed a self-supervised learning</div></section></section></section><section><section id="sec3"><section id="sec3.1"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Materials and data preprocessing</h2><div class="u-margin-s-bottom" id="d1e9453">Two datasets with rs-fMRI scans are used in the experiments, including (1) REST-meta-MDD Consortium (REST-MDD)<sup>1</sup> and (2) Autism Brain Imaging Data Exchange (ABIDE).<sup>2</sup> For each dataset, we use the top three largest sites in the experiments. Specifically, the largest site is utilized to train the pretext model to acquire general fMRI feature representations, and the remaining sites are utilized to fine-tune the</div></section></section></section><section><section id="sec4"><section id="sec4.1"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Experimental settings</h2><div class="u-margin-s-bottom" id="d1e14151">In this work, we conduct cross-site brain disease classification, where we first pre-train a pretext model using one imaging site and then fine-tune it on other sites. Two groups of experiments are performed, which are detailed as follows. (1) We perform MDD vs. HC classification using REST-MDD dataset. The pretext model is trained on the largest site (Site <span class="math"><math><mrow is="true"><mn is="true">20</mn></mrow></math></span>), and Site <span class="math"><math><mn is="true">1</mn></math></span> and Site <span class="math"><math><mrow is="true"><mn is="true">21</mn></mrow></math></span> are used for model fine-tuning and test, respectively. (2) We perform ASD vs. HC classification on ABIDE</div></section></section></section><section><section id="sec5"><section id="sec5.1"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Ablation study</h2><div class="u-margin-s-bottom" id="d1e14720">To investigate the importance of our introduced GDA module, we compare GCDA with its three variants, <em>i.e.</em>, <strong>GCDAw/oNODE</strong>, <strong>GCDAw/oEDGE</strong>, and <strong>GCDAw/oT</strong>. In GCDAw/oNODE, only the diffusion of edge features is used during the forward process, while the step of adding noise to node features is removed. In GCDAw/oEDGE, only the diffusion of node features is utilized, while the noise addition on edge features is omitted. The GCDAw/oT method discards the denoising neural network and only performs diffusion </div></section></section></section><section><section id="sec6"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">Conclusion</h2><div class="u-margin-s-bottom" id="d1e16132">This work presents a self-supervised graph contrastive learning framework with diffusion augmentation (GCDA) for functional MRI analysis. The GCDA comprises a pretext model for pre-training and a task-specific model for fine-tuning. In the pretext model, we first augment each brain functional connectivity network derived from fMRI through a graph diffusion augmentation module, and then use two graph isomorphism networks with shared parameters to extract features in a self-supervised contrastive </div></section></section><section><section id="d1e16134"><h2 class="section-title u-h4 u-margin-l-top u-margin-xs-bottom">CRediT authorship contribution statement</h2><div class="u-margin-s-bottom" id="d1e16137"><strong>Xiaochuan Wang:</strong> Writing – original draft, Software, Methodology. <strong>Yuqi Fang:</strong> Writing – review &amp; editing. <strong>Qianqian Wang:</strong> Writing – review &amp; editing. <strong>Pew-Thian Yap:</strong> Writing – review &amp; editing. <strong>Hongtu Zhu:</strong> Writing – review &amp; editing. <strong>Mingxia Liu:</strong> Writing – review &amp; editing, Validation, Supervision, Conceptualization.</div></section></section><section><section id="coi1"><h2 id="d1e16157" class="u-h4 u-margin-l-top u-margin-xs-bottom">Declaration of competing interest</h2><div class="u-margin-s-bottom" id="d1e16159">The authors declare that they have no known competing financial interests or personal relationships that could have appeared to influence the work reported in this paper.</div></section></section><section><section id="d1e16161"><h2 id="d1e16162" class="u-h4 u-margin-l-top u-margin-xs-bottom">Acknowledgments</h2><div class="u-margin-s-bottom" id="d1e16164">The research of P. Yap, H. Zhu and M. Liu was supported in part by the <span id="GS1">National Institutes of Health (NIH), United States</span> , under award numbers <span>AG073297</span>, <span>AG082938</span>, <span>EB035160</span>, and <span>NS134849</span>.</div></section></section></div></div><div class="related-content-links u-display-none-from-md"><button class="button-link button-link-primary button-link-small" type="button"><span class="button-link-text-container"><span class="button-link-text">Recommended articles</span></span></button></div><div class="Tail"></div><div id="preview-section-references"><div class="paginatedReferences u-font-serif"><div class="PageDivider"></div><header><h2 class="u-h4 u-margin-l-ver"><span>References</span><span> (70)</span></h2></header><ul><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>S. </span>Amemiya</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S105381191600238X"><span class="anchor-text-container"><span class="anchor-text">Global and structured waves of rs-fMRI signal identified as putative propagation of spontaneous neural activity</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Neuroimage</h3></div><div class="series">(2016)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>E. </span>Bondi</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S0149763422004614"><span class="anchor-text-container"><span class="anchor-text">A systematic review on the potential use of machine learning to classify major depressive disorder from healthy controls using resting state fMRI measures</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Neurosci. Biobehav. Rev.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>W. </span>Cui</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S0010482523002147"><span class="anchor-text-container"><span class="anchor-text">Dynamic multi-site graph convolutional network for autism spectrum disorder identification</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Comput. Biol. Med.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>P. </span>Dai</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S016503272300928X"><span class="anchor-text-container"><span class="anchor-text">Classification of recurrent major depressive disorder using a new time series feature extraction method through multisite rs-fMRI data</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">J. Affect. Disord.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>C. </span>Ecker</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1474442215000502"><span class="anchor-text-container"><span class="anchor-text">Neuroimaging in autism spectrum disorder: Brain structure and function across the lifespan</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Lancet Neurol.</h3></div><div class="series">(2015)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>Y. </span>Fang</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1361841522003358"><span class="anchor-text-container"><span class="anchor-text">Unsupervised cross-domain functional MRI adaptation for automated major depressive disorder identification</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Med. Image Anal.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>A. </span>Fedorov</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1053811923006353"><span class="anchor-text-container"><span class="anchor-text">Self-supervised multimodal learning for group inferences from MRI data: Discovering disorder-relevant brain regions and multimodal links</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Neuroimage</h3></div><div class="series">(2024)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>X. </span>Li</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1361841520301298"><span class="anchor-text-container"><span class="anchor-text">Multi-site fMRI analysis using privacy-preserving federated learning and domain adaptation: ABIDE results</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Med. Image Anal.</h3></div><div class="series">(2020)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>H. </span>Li</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1361841523000178"><span class="anchor-text-container"><span class="anchor-text">Computing personalized brain functional networks from fMRI using self-supervised deep learning</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Med. Image Anal.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>Z. </span>Mao</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S0020025519304475"><span class="anchor-text-container"><span class="anchor-text">Spatio-temporal deep learning method for adhd fMRI classification</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Inform. Sci.</h3></div><div class="series">(2019)</div></span></li></ul><div class="u-display-none"><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>M.B. </span>Nebel</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1053811922004153"><span class="anchor-text-container"><span class="anchor-text">Accounting for motion in resting-state fMRI: What part of the spectrum are we characterizing in autism spectrum disorder?</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Neuroimage</h3></div><div class="series">(2022)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>C. </span>Oh</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1877050920316914"><span class="anchor-text-container"><span class="anchor-text">Time-series data augmentation based on interpolation</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Procedia Comput. Sci.</h3></div><div class="series">(2020)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>W. </span>Peng</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S0165032716301070"><span class="anchor-text-container"><span class="anchor-text">Essential brain structural alterations in major depressive disorder: A voxel-wise meta-analysis on first episode, medication-naive patients</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">J. Affect. Disord.</h3></div><div class="series">(2016)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>W.R. </span>Shirer</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S105381191500395X"><span class="anchor-text-container"><span class="anchor-text">Optimization of rs-fMRI pre-processing for enhanced signal-noise separation, test-retest reliability, and group discrimination</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Neuroimage</h3></div><div class="series">(2015)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>M.W. </span>Weiner</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1552526013024291"><span class="anchor-text-container"><span class="anchor-text">The alzheimer’s disease neuroimaging initiative: A review of papers published since its inception</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Alzheimer’s &amp; Dementia</h3></div><div class="series">(2013)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>S. </span>Zhang</span><em> et al.</em></span><h3><a class="anchor title anchor-primary" href="/science/article/pii/S1361841523001925"><span class="anchor-text-container"><span class="anchor-text">A-GCL: Adversarial graph contrastive learning for fMRI analysis to diagnose neurodevelopmental disorders</span></span></a></h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Med. Image Anal.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>A. </span>Bessadok</span><em> et al.</em></span><h3 class="title">Graph neural networks in network neuroscience</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">IEEE Trans. Pattern Anal. Mach. Intell.</h3></div><div class="series">(2022)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>J. </span>Bijsterbosch</span><em> et al.</em></span><h3 class="title">An Introduction to Resting State fMRI Functional Connectivity</h3><span class="host u-clr-grey6 u-font-sans"><div class="series">(2017)</div></span></li><li class="bib-reference u-margin-s-bottom"><span>Chen, X., He, K., 2021. Exploring simple Siamese representation learning. In: Proceedings of the IEEE/CVF Conference on...</span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>T. </span>Chen</span><em> et al.</em></span><h3 class="title">A simple framework for contrastive learning of visual representations</h3><span class="host u-clr-grey6 u-font-sans"></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>B.U. </span>Demirel</span><em> et al.</em></span><h3 class="title">Finding order in chaos: A novel data augmentation method for time series in contrastive learning</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Adv. Neural Inf. Process. Syst.</h3></div><div class="series">(2024)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>V.P. </span>Dwivedi</span><em> et al.</em></span><h3 class="title">A generalization of transformer networks to graphs</h3><span class="host u-clr-grey6 u-font-sans"><div class="series">(2020)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>L. </span>Ericsson</span><em> et al.</em></span><h3 class="title">Self-supervised representation learning: Introduction, advances, and challenges</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">IEEE Signal Process. Mag.</h3></div><div class="series">(2022)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>H. </span>Guan</span><em> et al.</em></span><h3 class="title">Domain adaptation for medical image analysis: A survey</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">IEEE Trans. Biomed. Eng.</h3></div><div class="series">(2021)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>X. </span>Guo</span><em> et al.</em></span><h3 class="title">A systematic survey on deep generative models for graph generation</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">IEEE Trans. Pattern Anal. Mach. Intell.</h3></div><div class="series">(2022)</div></span></li><li class="bib-reference u-margin-s-bottom"><span>He, K., Fan, H., Wu, Y., Xie, S., Girshick, R., 2020. Momentum contrast for unsupervised visual representation...</span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>B. </span>Hebling Vieira</span><em> et al.</em></span><h3 class="title">A deep learning based approach identifies regions more relevant than resting-state networks to the prediction of general intelligence from resting-state fMRI</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Hum. Brain Mapp.</h3></div><div class="series">(2021)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>D. </span>Hendrycks</span><em> et al.</em></span><h3 class="title">Using self-supervised learning can improve model robustness and uncertainty</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Adv. Neural Inf. Process. Syst.</h3></div><div class="series">(2019)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>J. </span>Ho</span><em> et al.</em></span><h3 class="title">Denoising diffusion probabilistic models</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Adv. Neural Inf. Process. Syst.</h3></div><div class="series">(2020)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>X. </span>Hou</span><em> et al.</em></span><h3 class="title">Deep-learning-enabled brain hemodynamic mapping using resting-state fMRI</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">NPJ Digit. Med.</h3></div><div class="series">(2023)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>M. </span>Ingalhalikar</span><em> et al.</em></span><h3 class="title">Functional connectivity-based prediction of autism on site harmonized ABIDE dataset</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">IEEE Trans. Biomed. Eng.</h3></div><div class="series">(2021)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>E. </span>Jang</span><em> et al.</em></span><h3 class="title">Categorical reparameterization with gumbel-softmax</h3><span class="host u-clr-grey6 u-font-sans"><div class="series">(2016)</div></span></li><li class="bib-reference u-margin-s-bottom"><span>Jiang, Y., Yang, Y., Xia, L., Huang, C., 2024. DiffKG: Knowledge Graph Diffusion Model for Recommendation. In:...</span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>B.H. </span>Kim</span><em> et al.</em></span><h3 class="title">Learning dynamic graph representation of brain connectome with spatio-temporal attention</h3><span class="host u-clr-grey6 u-font-sans"><div class="series"><h3 class="title">Adv. Neural Inf. Process. Syst.</h3></div><div class="series">(2021)</div></span></li><li class="bib-reference u-margin-s-bottom"><span class="u-font-sans"><span class="author u-font-sans"><span>D.P. </span>Kingma</span><em> et al.</em></span><h3 class="title">Adam: A method for stochastic optimization</h3><span class="host u-clr-grey6 u-font-sans"><div class="series">(2014)</div></span></li></div><button class="button-alternative button-alternative-secondary u-font-sans u-margin-l-bottom large-alternative button-alternative-icon-left" type="button" id="show-more-refs-btn"><svg focusable="false" viewBox="0 0 92 128" height="20" class="icon icon-navigate-down"><path d="M1 51l7-7 38 38 38-38 7 7-45 45z"></path></svg><span class="button-alternative-text-container"><span class="button-alternative-text">View more references</span></span></button></div></div><div id="preview-section-cited-by"><section aria-label="Cited by" class="ListArticles preview"><div class="PageDivider"></div><header id="citing-articles-header"><h2 class="u-h4 u-margin-l-ver u-font-serif">Cited by (0)</h2></header><div aria-describedby="citing-articles-header"></div></section></div><div class="PageDivider"></div><a class="anchor full-text-link anchor-primary" href="/science/article/pii/S1361841524003281" aria-disabled="true" tabindex="-1"><span class="anchor-text-container"><span class="anchor-text">View full text</span></span></a><div class="Copyright"><span class="copyright-line">© 2024 Elsevier B.V. All rights are reserved, including those for text and data mining, AI training, and similar technologies.</span></div></article><div class="u-display-block-from-md col-lg-6 col-md-8 pad-right u-padding-s-top"><aside class="RelatedContent u-clr-grey8" aria-label="Related content"><section class="RelatedContentPanel u-margin-s-bottom"><header id="recommended-articles-header" class="related-content-panel-header u-margin-s-bottom"><button class="button-link button-link-secondary related-content-panel-toggle is-up button-link-icon-right button-link-has-colored-icon" type="button" aria-expanded="true" data-aa-button="sd:product:journal:article:location=recommended-articles:type=close"><span class="button-link-text-container"><span class="button-link-text"><h2 class="section-title u-h4"><span class="related-content-panel-title-text">Recommended articles</span></h2></span></span><svg focusable="false" viewBox="0 0 92 128" height="20" class="icon icon-navigate-down"><path d="M1 51l7-7 38 38 38-38 7 7-45 45z"></path></svg></button></header><div class="" aria-hidden="false" aria-describedby="recommended-articles-header"><div id="recommended-articles" class="text-xs"><ul><li class="RelatedContentPanelItem u-display-block"><div class="sub-heading u-padding-xs-bottom"><h3 class="related-content-panel-list-entry-outline-padding text-s u-font-serif" id="recommended-articles-article0-title"><a class="anchor u-clamp-2-lines anchor-primary" href="/science/article/pii/S136184152400375X" title="Domain-specific information preservation for Alzheimer’s disease diagnosis with incomplete multi-modality neuroimages"><span class="anchor-text-container"><span class="anchor-text"><span>Domain-specific information preservation for Alzheimer’s disease diagnosis with incomplete multi-modality neuroimages</span></span></span></a></h3><div class="article-source u-clr-grey6"><div class="source">Medical Image Analysis, Volume 101, 2025, Article 103448</div></div><div class="authors"><span>Haozhe</span> <span>Xu</span>, …, <span>Zhenyuan</span> <span>Ning</span></div></div><div class="buttons"></div></li><li class="RelatedContentPanelItem u-display-block"><div class="sub-heading u-padding-xs-bottom"><h3 class="related-content-panel-list-entry-outline-padding text-s u-font-serif" id="recommended-articles-article1-title"><a class="anchor u-clamp-2-lines anchor-primary" href="/science/article/pii/S1361841524003244" title="Multi-scale region selection network in deep features for full-field mammogram classification"><span class="anchor-text-container"><span class="anchor-text"><span>Multi-scale region selection network in deep features for full-field mammogram classification</span></span></span></a></h3><div class="article-source u-clr-grey6"><div class="source">Medical Image Analysis, Volume 100, 2025, Article 103399</div></div><div class="authors"><span>Luhao</span> <span>Sun</span>, …, <span>Chao</span> <span>Li</span></div></div><div class="buttons"></div></li><li class="RelatedContentPanelItem u-display-block"><div class="sub-heading u-padding-xs-bottom"><h3 class="related-content-panel-list-entry-outline-padding text-s u-font-serif" id="recommended-articles-article2-title"><a class="anchor u-clamp-2-lines anchor-primary" href="/science/article/pii/S1361841524003499" title="Learnable color space conversion and fusion for stain normalization in pathology images"><span class="anchor-text-container"><span class="anchor-text"><span>Learnable color space conversion and fusion for stain normalization in pathology images</span></span></span></a></h3><div class="article-source u-clr-grey6"><div class="source">Medical Image Analysis, Volume 101, 2025, Article 103424</div></div><div class="authors"><span>Jing</span> <span>Ke</span>, …, <span>Dinggang</span> <span>Shen</span></div></div><div class="buttons"></div></li><li class="RelatedContentPanelItem u-display-none"><div class="sub-heading u-padding-xs-bottom"><h3 class="related-content-panel-list-entry-outline-padding text-s u-font-serif" id="recommended-articles-article3-title"><a class="anchor u-clamp-2-lines anchor-primary" href="/science/article/pii/S1361841524003578" title="AutoFOX: An automated cross-modal 3D fusion framework of coronary X-ray angiography and OCT"><span class="anchor-text-container"><span class="anchor-text"><span>AutoFOX: An automated cross-modal 3D fusion framework of coronary X-ray angiography and OCT</span></span></span></a></h3><div class="article-source u-clr-grey6"><div class="source">Medical Image Analysis, Volume 101, 2025, Article 103432</div></div><div class="authors"><span>Chunming</span> <span>Li</span>, …, <span>Shengxian</span> <span>Tu</span></div></div><div class="buttons"></div></li><li class="RelatedContentPanelItem u-display-none"><div class="sub-heading u-padding-xs-bottom"><h3 class="related-content-panel-list-entry-outline-padding text-s u-font-serif" id="recommended-articles-article4-title"><a class="anchor u-clamp-2-lines anchor-primary" href="/science/article/pii/S1361841524003645" title="Personalized dental crown design: A point-to-mesh completion network"><span class="anchor-text-container"><span class="anchor-text"><span>Personalized dental crown design: A point-to-mesh completion network</span></span></span></a></h3><div class="article-source u-clr-grey6"><div class="source">Medical Image Analysis, Volume 101, 2025, Article 103439</div></div><div class="authors"><span>Golriz</span> <span>Hosseinimanesh</span>, …, <span>Francois</span> <span>Guibault</span></div></div><div class="buttons"></div></li><li class="RelatedContentPanelItem u-display-none"><div class="sub-heading u-padding-xs-bottom"><h3 class="related-content-panel-list-entry-outline-padding text-s u-font-serif" id="recommended-articles-article5-title"><a class="anchor u-clamp-2-lines anchor-primary" href="/science/article/pii/S1361841524003098" title="TSdetector: Temporal–Spatial self-correction collaborative learning for colonoscopy video detection"><span class="anchor-text-container"><span class="anchor-text"><span>TSdetector: Temporal–Spatial self-correction collaborative learning for colonoscopy video detection</span></span></span></a></h3><div class="article-source u-clr-grey6"><div class="source">Medical Image Analysis, Volume 100, 2025, Article 103384</div></div><div class="authors"><span>Kai-Ni</span> <span>Wang</span>, …, <span>Shuo</span> <span>Li</span></div></div><div class="buttons"></div></li></ul></div><button class="button-link more-recommendations-button u-margin-s-bottom button-link-primary button-link-icon-right" type="button"><span class="button-link-text-container"><span class="button-link-text">Show 3 more articles</span></span><svg focusable="false" viewBox="0 0 92 128" height="20" class="icon icon-navigate-down"><path d="M1 51l7-7 38 38 38-38 7 7-45 45z"></path></svg></button></div></section></aside></div></div></div></div><footer role="contentinfo" class="els-footer u-bg-white text-xs u-padding-s-hor u-padding-m-hor-from-sm u-padding-l-hor-from-md u-padding-l-ver u-margin-l-top u-margin-xl-top-from-sm u-margin-l-top-from-md"><div class="els-footer-elsevier u-margin-m-bottom u-margin-0-bottom-from-md u-margin-s-right u-margin-m-right-from-md u-margin-l-right-from-lg"><a class="anchor anchor-primary anchor-icon-left anchor-with-icon" href="https://www.elsevier.com/" target="_blank" aria-label="Elsevier home page (opens in a new tab)"><img class="footer-logo" src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/47/images/elsevier-non-solus-new-with-wordmark.svg" alt="Elsevier logo with wordmark" height="64" width="58" loading="lazy"/></a></div><div class="els-footer-content"><div class="u-remove-if-print"><ul class="els-footer-links u-margin-xs-bottom" style="list-style:none"><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="https://www.elsevier.com/solutions/sciencedirect" target="_blank" id="els-footer-about-science-direct" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">About ScienceDirect</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></li><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="/user/institution/login?targetURL=%2Fscience%2Farticle%2Fpii%2FS1361841524003281" id="els-footer-remote-access" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">Remote access</span></span></a></li><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="https://sd-cart.elsevier.com/?" target="_blank" id="els-footer-shopping-cart" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">Shopping cart</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></li><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="https://www.elsmediakits.com" target="_blank" id="els-footer-advertise" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">Advertise</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></li><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="https://service.elsevier.com/app/contact/supporthub/sciencedirect/" target="_blank" id="els-footer-contact-support" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">Contact and support</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></li><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="https://www.elsevier.com/legal/elsevier-website-terms-and-conditions" target="_blank" id="els-footer-terms-condition" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">Terms and conditions</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></li><li><a class="anchor u-display-flex u-clr-grey8 u-margin-s-bottom u-margin-0-bottom-from-sm u-margin-m-right-from-sm u-margin-l-right-from-md anchor-primary anchor-small" href="https://www.elsevier.com/legal/privacy-policy" target="_blank" id="els-footer-privacy-policy" rel="nofollow"><span class="anchor-text-container"><span class="anchor-text">Privacy policy</span><svg focusable="false" viewBox="0 0 8 8" height="20" aria-label="Opens in new window" class="icon icon-arrow-up-right-tiny arrow-external-link"><path d="M1.12949 2.1072V1H7V6.85795H5.89111V2.90281L0.784057 8L0 7.21635L5.11902 2.1072H1.12949Z"></path></svg></span></a></li></ul></div><p id="els-footer-cookie-message" class="u-remove-if-print">Cookies are used by this site. <!-- --> <button class="button-link ot-sdk-show-settings cookie-btn button-link-primary button-link-small" type="button" id="ot-sdk-btn"><span class="button-link-text-container"><span class="button-link-text"><strong>Cookie Settings</strong></span></span></button></p><p id="els-footer-copyright">All content on this site: Copyright © <!-- -->2025<!-- --> or its licensors and contributors. All rights are reserved, including those for text and data mining, AI training, and similar technologies. For all open access content, the relevant licensing terms apply.</p></div><div class="els-footer-relx u-margin-0-top u-margin-m-top-from-xs u-margin-0-top-from-md"><a class="anchor anchor-primary anchor-icon-left anchor-with-icon" href="https://www.relx.com/" target="_blank" aria-label="RELX home page (opens in a new tab)" id="els-footer-relx"><img class="" src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/60/images/logo-relx-tm.svg" alt="RELX group home page" height="20" width="93" loading="lazy"/></a></div></footer></div></div></div></div>
      <div id="floating-ui-node" class="floating-ui-node" data-sd-ui-floating-ui="true"></div>
      
      <script src="https://assets.adobedtm.com/4a848ae9611a/032db4f73473/launch-a6263b31083f.min.js" type="48d55d7d34a7ef35ff792557-text/javascript" async></script>
      
<script type="48d55d7d34a7ef35ff792557-text/javascript">
    window.pageData = {"content":[{"contentType":"JL","format":"MIME-XHTML","id":"sd:article:pii:S1361841524003281","type":"sd:article:JL:scope-abstract","detail":"sd:article:subtype:fla","publicationType":"journal","issn":"1361-8415","volumeNumber":"101","suppl":"C","provider":"elsevier","entitlementType":"unsubscribed"}],"page":{"businessUnit":"ELS:RP:ST","language":"en","name":"product:journal:article","noTracking":"false","productAppVersion":"abstract-direct","productName":"SD","type":"CP-CA","environment":"prod","loadTimestamp":1739780256982,"loadTime":""},"visitor":{"accessType":"ae:ANON_GUEST","accountId":"ae:228598","accountName":"ae:ScienceDirect Guests","loginStatus":"anonymous","userId":"ae:12975512","ipAddress":"106.205.96.253","appSessionId":"7bfbd3ed-46a2-46ae-9a58-2f93297c2d4c"}};
    window.pageData.page.loadTime = performance ? Math.round(performance.now()).toString() : '';

    try {
      appData.push({
      event: 'pageLoad',
      page: pageData.page,
      visitor: pageData.visitor,
      content: pageData.content
      })
    } catch(e) {
        console.warn("There was an error loading or running Adobe DTM: ", e);
    }
</script>
      <script nomodule src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/73/js/core-js/3.20.2/core-js.es.minified.js" type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/108/js/react/18.3.1/react.production.min.js" type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script src="https://sdfestaticassets-eu-west-1.sciencedirectassets.com/shared-assets/108/js/react-dom/18.3.1/react-dom.production.min.js" type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script src='https://sdfestaticassets-eu-west-1.sciencedirectassets.com/prod/44c3817e58b49348a73e63fb998fb7b2924522e1/arp.js' async type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script type="48d55d7d34a7ef35ff792557-text/javascript">
    const pendoData = {"visitor":{"pageName":"SD:product:journal:article","pageType":"CP-CA","pageProduct":"SD","pageLanguage":"en","pageEnvironment":"prod","accessType":"ae:ANON_GUEST","countryCode":"IN"},"account":{"id":"ae:228598","name":"ae:ScienceDirect Guests"},"events":{}};;
    pendoData.events = {
      ready: function () {
        pendo.addAltText();
      },
    };
    function runPendo(data, options) {
  const {
    firstDelay,
    maxRetries,
    urlPrefix,
    urlSuffix,
    apiKey
  } = options;
  (function (apiKey) {
    (function (p, e, n, d, o) {
      var v, w, x, y, z;
      o = p[d] = p[d] || {};
      o._q = [];
      v = ['initialize', 'identify', 'updateOptions', 'pageLoad'];
      for (w = 0, x = v.length; w < x; ++w) (function (m) {
        o[m] = o[m] || function () {
          o._q[m === v[0] ? 'unshift' : 'push']([m].concat([].slice.call(arguments, 0)));
        };
      })(v[w]);
      y = e.createElement(n);
      y.async = !0;
      y.src = urlPrefix + apiKey + urlSuffix;
      z = e.getElementsByTagName(n)[0];
      z.parentNode.insertBefore(y, z);
    })(window, document, 'script', 'pendo');
    pendo.addAltText = function () {
      var target = document.querySelector('body');
      var observer = new MutationObserver(function (mutations) {
        mutations.forEach(function (mutation) {
          if (mutation?.addedNodes?.length) {
            if (mutation.addedNodes[0]?.className?.includes("_pendo-badge")) {
              const badge = mutation.addedNodes[0];
              const altText = badge?.attributes['aria-label'].value ? badge?.attributes['aria-label'].value : 'Feedback';
              const pendoBadgeImage = pendo.dom(`#${badge?.attributes?.id.value} img`);
              if (pendoBadgeImage.length) {
                pendoBadgeImage[0]?.setAttribute('alt', altText);
              }
            }
          }
        });
      });
      var config = {
        attributeFilter: ['data-layout'],
        attributes: true,
        childList: true,
        characterData: true,
        subtree: false
      };
      observer.observe(target, config);
    };
  })(apiKey);
  (function watchAndSetPendo(nextDelay, retryAttempt) {
    if (typeof pageDataTracker === 'object' && typeof pageDataTracker.getVisitorId === 'function' && pageDataTracker.getVisitorId()) {
      data.visitor.id = pageDataTracker.getVisitorId();
      console.debug(`initializing pendo`);
      pendo.initialize(data);
    } else {
      if (retryAttempt > 0) {
        return setTimeout(function () {
          watchAndSetPendo(nextDelay * 2, retryAttempt - 1);
        }, nextDelay);
      }
      pendo.initialize(data);
      console.debug(`gave up ... pendo initialized`);
    }
  })(firstDelay, maxRetries);
}
    runPendo(pendoData, {
      firstDelay: 100,
      maxRetries: 5,
      urlPrefix: 'https://cdn.pendo.io/agent/static/',
      urlSuffix: '/pendo.js',
      apiKey: 'd6c1d995-bc7e-4e53-77f1-2ea4ecbb9565',
    });
  </script>
      <span id="pendo-answer-rating"></span>
      <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
          displayAlign: 'left',
          "fast-preview": {
            disabled: true
          },
          CommonHTML: { linebreaks: { automatic: true } },
          PreviewHTML: { linebreaks: { automatic: true } },
          'HTML-CSS': { linebreaks: { automatic: true } },
          SVG: {
            scale: 90,
            linebreaks: { automatic: true }
          }
        });
      </script>
      <script async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=MML_SVG" type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script async src="https://www.googletagservices.com/tag/js/gpt.js" type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script async src="https://scholar.google.com/scholar_js/casa.js" type="48d55d7d34a7ef35ff792557-text/javascript"></script>
      <script data-cfasync="false">
      (function initOneTrust()  {
        const monitor = {
  init: () => {},
  loaded: () => {},
};
        function enableGroup(group) {
  document.querySelectorAll(`script[type*="ot-${group}"]`).forEach(script => {
    script.type = 'text/javascript';
    document.head.appendChild(script);
  });
}
        function runOneTrustCookies(doClear, monitor) {
  const oneTrustConsentSdkId = 'onetrust-consent-sdk';
  const emptyNodeSelectors = 'h3.ot-host-name, h4.ot-host-desc, button.ot-host-box';
  const ariaLabelledByButtonNodes = 'div.ot-accordion-layout > button';
  const ariaAttribute = 'aria-labelledby';
  function adjustOneTrustDOM() {
    const oneTrustRoot = document.getElementById('onetrust-consent-sdk');

    /* remove empty nodes */
    [...(oneTrustRoot?.querySelectorAll(emptyNodeSelectors) ?? [])].filter(e => e.textContent === '').forEach(e => e.remove());

    /* remove invalid aria-labelledby values */
    oneTrustRoot?.querySelectorAll(ariaLabelledByButtonNodes).forEach(e => {
      const presentIdValue = e.getAttribute(ariaAttribute)?.split(' ').filter(label => document.getElementById(label)).join(' ');
      if (presentIdValue) {
        e.setAttribute(ariaAttribute, presentIdValue);
      }
    });
  }
  function observeOneTrustLoaded(shouldSetOTDefaults, isConsentPresent) {
    const cb = (mutationList, observer) => {
      const oneTrustRoot = mutationList.filter(mutationRecord => mutationRecord.type === 'childList' && mutationRecord.addedNodes.length).map(mutationRecord => [...mutationRecord.addedNodes]).flat().find(e => e.id === oneTrustConsentSdkId);
      if (oneTrustRoot && typeof OneTrust !== 'undefined') {
        monitor.loaded(true);
        OneTrust.OnConsentChanged(() => {
          const perfAllowed = decodeURIComponent(document.cookie.match('(^| )OptanonConsent=([^;]+)')?.[2])?.match('groups=([0-9:0|1,?]+)&?')?.[1]?.match('2:([0|1])')[1] === '1';
          if (perfAllowed) {
            enableGroup('performance');
          }
        });
        if (!isConsentPresent && (shouldSetOTDefaults || OneTrust.GetDomainData().ConsentModel.Name === 'implied consent')) {
          OneTrust.AllowAll();
        }
        document.dispatchEvent(new CustomEvent('@sdtech/onetrust/loaded', {}));
        observer.disconnect();
        adjustOneTrustDOM();
      }
    };
    const observer = new MutationObserver(cb);
    observer.observe(document.querySelector('body'), {
      childList: true
    });
  }
  if (doClear) {
    document.cookie = 'OptanonAlertBoxClosed=; expires=Thu, 01 Jan 1970 00:00:00 UTC; samesite=lax; path=/';
  }
  const isConsentPresent = !!decodeURIComponent(document.cookie.match('(^| )OptanonConsent=([^;]+)')?.[2])?.match('groups=([0-9:0|1,?]+)&?')?.[1];
  const shouldSetOTDefaults = 'true' === 'false' && !document.cookie?.match('OptanonAlertBoxClosed=');
  if (shouldSetOTDefaults) {
    const date = new Date();
    date.setFullYear(date.getFullYear() + 1);
    document.cookie = `OptanonAlertBoxClosed=${new Date().toISOString()}; expires=${date.toUTCString()}; samesite=lax; path=/; domain=sciencedirect.com`;
  }
  observeOneTrustLoaded(shouldSetOTDefaults, isConsentPresent, monitor);
  window.addOTScript = () => {
    const otSDK = document.createElement('script');
    otSDK.setAttribute('data-cfasync', 'false');
    otSDK.setAttribute('src', 'https://cdn.cookielaw.org/scripttemplates/otSDKStub.js');
    otSDK.setAttribute('data-document-language', 'true');
    otSDK.setAttribute('data-domain-script', '865ea198-88cc-4e41-8952-1df75d554d02');
    window.addOTScript = () => {};
    document.head.appendChild(otSDK);
    monitor.init();
  };
  window.addEventListener('load', () => window.addOTScript());
}
        if (document.location.host.match(/.sciencedirect.com$/)) {
          runOneTrustCookies(true, monitor);
        }
        else {
          window.addEventListener('load', (event) => {
            enableGroup('performance');
          });
        }
      }());
    </script>
    <script src="/cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js" data-cf-settings="48d55d7d34a7ef35ff792557-|49" defer></script></body>
  </html>
