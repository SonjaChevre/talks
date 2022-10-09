![Kubernetes Community Days Munich 2022](https://github.com/SonjaChevre/talks/blob/main/2022-10_k8s_community_munich/munich_k8s_community_days.png?raw=true)

# Is now a good time to migrate from OpenTracing to OpenTelemetry?

Talk given at the [Kubernetes Community Days Munich 2022](https://community.cncf.io/events/details/cncf-kcd-munich-presents-kubernetes-community-days-munich-2022-1/) - connect with the awesome Kubernetes Community from Munich on [Twitter](https://twitter.com/KCDMunich) and [LinkedIn](https://www.linkedin.com/company/kubernetes-community-days-munich/).

## Get in touch

You can reach me on [Twitter](https://twitter.com/SonjaChevre) and [LinkedIn](https://www.linkedin.com/in/sonjachevre/).

## Abstract

OpenTelemetry, the project created from the merger of OpenTracing and OpenCensus is now three years old. If you had previously integrated OpenTracing or OpenCensus in your applications, you might be asking yourself: What will I gain from migrating to OpenTelemetry? Is OpenTelemetry tracing stable enough? What are the aspects to consider for a successful migration? After working for more than seven years in the observability space, I joined this year a new company and started to ask myself those exact questions. Join me on my learning journey as I look for answers.

## Slide deck

[Slide deck (PDF)](https://github.com/SonjaChevre/talks/blob/main/2022-10_k8s_community_munich/OpenTracing_OpenTelemetry_Sonja_Chevre_2022-10.pdf)

!(https://github.com/SonjaChevre/talks/blob/main/2022-10_k8s_community_munich/OpenTracing_OpenTelemetry_Sonja_Chevre_2022-10.pdf?raw=true)
 
## Reference and useful links

* Distributions and vendors who natively support OpenTelemetry in their commercial products: https://opentelemetry.io/vendors
* CNCF open source projects popularity: https://docs.google.com/spreadsheets/d/1JdAZrQx52m3XVzloE7KK5ciI-Xu-P-swGxdV3T9pXoY
* OpenTelemetry Project Status: What to know (second part of the blog post): https://medium.com/@team_Aspecto/profiling-with-opentelemetry-say-what-now-language-support-status-78f94c7557a7
* Keynote: State of the Community - Morgan McLean & Alolita Sharma, OTel Gov Cmte: https://www.youtube.com/watch?v=XUzjWITlU3c
* CNCF archives the OpenTracing project: https://www.cncf.io/blog/2022/01/31/cncf-archives-the-opentracing-project/ 
* Status OpenTelemetry: https://opentelemetry.io/status/
* Migrating from OpenTracing to OpenTelemetry: https://opentelemetry.io/docs/migration/opentracing/
* Envoy & OpenTelemetry support
   * https://github.com/envoyproxy/envoy/issues/9958
   * https://www.envoyproxy.io/docs/envoy/latest/api-v3/config/trace/v3/opentelemetry.proto#config-trace-v3-opentelemetryconfig 
* Linkerd & OpenTelemetry support
   * https://github.com/linkerd/linkerd2/issues/5417
   * https://linkerd.io/2.12/tasks/distributed-tracing/ 
   * https://github.com/linkerd/linkerd2/issues/6159 
* Context propagation explained: https://www.youtube.com/watch?v=gviWKCXwyvY 
* AWS X-ray tracing: https://docs.aws.amazon.com/xray/latest/devguide/xray-concepts.html#xray-concepts-traces
* Use attributes that can explain performance variation: https://lightstep.com/opentelemetry/best-practices/otel-attributes 
* OpenTelemetry sampling: https://uptrace.dev/opentelemetry/sampling.html#head-based-sampling  
* How insecure application tracing and telemetry may lead to sensitive data and PII leakage: https://www.oxeye.io/blog/how-insecure-application-tracing-and-telemetry-may-lead-to-sensitive-data-and-pii-leakage 
* Use OpenTelemetry processors to change collected backend data: https://www.splunk.com/en_us/blog/devops/why-to-use-opentelemetry-processors-to-change-collected-backend-data.html 
* Tyk Gateway performance testing: https://github.com/TykTechnologies/tyk-ansible-performance-testing





