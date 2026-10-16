<p align="center">
  <a href="https://swarup.me">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0b0907%2C55:2a1a0c%2C100:5a3412&text=Swarup%20E&fontColor=ffb054&fontSize=72&fontAlignY=36&desc=Lead%20Engineer%20%C2%B7%20full-stack%20systems%20%C2%B7%20Bengaluru&descSize=20&descAlignY=58&animation=fadeIn" />
      <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:fbf3e6,55:f6dcb4,100:ffb054&text=Swarup%20E&fontColor=3a2412&fontSize=72&fontAlignY=36&desc=Lead%20Engineer%20%C2%B7%20full-stack%20systems%20%C2%B7%20Bengaluru&descSize=20&descAlignY=58&animation=fadeIn" alt="Swarup E, Lead Engineer, full-stack systems, Bengaluru" width="100%" />
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://swarup.me">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=800&color=FFB054&amp;center=true&vCenter=true&width=820&height=40&lines=%24+swc+swarup.src+--release;Probing+20+targets+..........+ok;Compiling+backend%2C+devops%2C+data%2C+frontend%2C+research%2C+side;Removing+dead+%7B+2017%2C+2018+%7D;Running+.%2Fswarup.bin" />
      <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=800&color=B8640F&amp;center=true&vCenter=true&width=820&height=40&lines=%24+swc+swarup.src+--release;Probing+20+targets+..........+ok;Compiling+backend%2C+devops%2C+data%2C+frontend%2C+research%2C+side;Removing+dead+%7B+2017%2C+2018+%7D;Running+.%2Fswarup.bin" alt="$ swc swarup.src --release. Compiling backend, devops, data, frontend, research, side. Running ./swarup.bin" />
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://swarup.me"><img src="https://img.shields.io/badge/swarup.me-0b0907?style=for-the-badge&logo=googlechrome&logoColor=FFB054" alt="Website" /></a>
  <a href="mailto:enamakalswarup@gmail.com"><img src="https://img.shields.io/badge/Email-ffb054?style=for-the-badge&logo=gmail&logoColor=0b0907" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/swarupe"><img src="https://img.shields.io/badge/LinkedIn-6fb4ff?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHJlY3QgeD0iMyIgeT0iOSIgd2lkdGg9IjQiIGhlaWdodD0iMTIiIGZpbGw9IndoaXRlIi8+PGNpcmNsZSBjeD0iNSIgY3k9IjQuNSIgcj0iMi4zIiBmaWxsPSJ3aGl0ZSIvPjxwYXRoIGQ9Ik0xMCA5aDMuOHYxLjhjLjYtMS4xIDItMi4xIDQtMi4xIDMuMyAwIDQuMiAyLjEgNC4yIDUuMlYyMWgtNHYtNi4yYzAtMS41LS4zLTIuOC0xLjktMi44cy0yLjEgMS4yLTIuMSAyLjhWMjFoLTR6IiBmaWxsPSJ3aGl0ZSIvPjwvc3ZnPg==" alt="LinkedIn" /></a>
  <a href="https://x.com/swarup_e"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://www.instagram.com/swarupe7"><img src="https://img.shields.io/badge/Instagram-ff7a5c?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://scholar.google.com/citations?user=Yp5J5mEAAAAJ"><img src="https://img.shields.io/badge/Scholar-9be37a?style=for-the-badge&logo=googlescholar&logoColor=0b0907" alt="Google Scholar" /></a>
</p>

I'm Lead Engineer at the **Centre of Data for Public Good** in Bengaluru, and I've been shipping software since 2019. I build backend services, run the Kubernetes platforms under them, move data through streaming pipelines into analytics stores, and build the front ends on top. Since Aug 2025 I'm also on the online M.Tech in Data Science and Business Analytics at IISc.

My site, [swarup.me](https://swarup.me), compiles this profile in 3D. Here is the source and the build.

```text
// swarup.src
module swarup_e {
  role  = "Lead Engineer"
  org   = "CDPG"
  city  = "Bengaluru"
  since = 2019
  study = "M.Tech, IISc"

  areas = [backend, devops, data,
           frontend, research, side]

  dead {  // unreachable
    student_projects(2017)
    student_projects(2018)
  }

  fn ship(idea) -> system {
    idea |> build |> run |> observe
  }

  export contact
}
```

```console
$ swc swarup.src --release
 self-test  toolchain ................ ok
   Probing  20 targets
  Indexing  swarup.src  333 commits  (178 + 70 + 85 across 3 repos)
 Compiling  backend (4 units)
            devops / kubernetes (4 units)
            data (3 units)
            frontend (3 units)
            research (3 units)
            side projects (3 units)
  Removing  dead { 2017, 2018 }
  Finished  release [optimized]
   Running  ./swarup.bin
```

## htop

| AREA | COMMAND | What it does |
|:--|:--|:--|
| ![backend](https://img.shields.io/badge/backend-6fb4ff?style=flat-square) | **IUDX Data Sandbox** | Jupyter notebooks next to datasets. Go API with Keycloak JWT auth, build progress over Server-Sent Events, JupyterHub and BinderHub on Kubernetes. 70 of 93 backend commits. |
| ![backend](https://img.shields.io/badge/backend-6fb4ff?style=flat-square) | **Data marketplace file service** | TypeScript and Express. S3 and MinIO multipart uploads, presigned URLs, Keycloak and policy checks, a Redis job queue. 85 of 105 commits. |
| ![data](https://img.shields.io/badge/data-9be37a?style=flat-square) | **IUDX Adaptor Framework** | Ingest pipeline on Apache Flink with a Calcite SQL rules engine over RocksDB state. Top contributor, 178 of 435 commits. |
| ![data](https://img.shields.io/badge/data-9be37a?style=flat-square) | **Analytics at volume** | ClickHouse clusters holding billions of rows with sub-second queries, fed by Azure Functions and Event Hubs. |
| ![devops](https://img.shields.io/badge/devops-b39dff?style=flat-square) | **Hybrid storage and clusters** | Ceph, MinIO and Kubernetes across cloud and on-prem, with GPU nodes. |
| ![devops](https://img.shields.io/badge/devops-b39dff?style=flat-square) | **Multi-kernel notebook images** | Python, R, Julia and Scala in one image. CPU image 16.1 GB to 8.1 GB, GPU image 38.9 GB to 26.5 GB. |
| ![backend](https://img.shields.io/badge/backend-6fb4ff?style=flat-square) | **IUDX Video Server** | Proxies live camera feeds from city servers behind NAT to the cloud, with load balancing and an API. |
| ![frontend](https://img.shields.io/badge/frontend-ffb054?style=flat-square) | **Parquet previews in the browser** | DuckDB in the marketplace file service, so datasets preview without a download. |
| ![research](https://img.shields.io/badge/research-ff7a5c?style=flat-square) | **LULC segmentation** | 4 papers on land use and land cover segmentation from satellite imagery. |
| ![side](https://img.shields.io/badge/side-5fd6c4?style=flat-square) | **GuideMesh, videopipe, agent-skills** | Walkthroughs that survive code changes (37 of 38 steps found 50 commits later), videos written as code, and 30 skills for coding agents. Private for now. |

## tail -f ~/career.log

```console
2019-02  latitude    [intern]   Chrome extension that records clicks into guided product tours
2019-07  epikindifi  [join]     Member of Technical Staff
2020     epikindifi  [ship]     Listings moved to GraphQL, 32% faster
2020     epikindifi  [ship]     KYC OCR with Tesseract and Detectron2 at 96% accuracy
2020-12  cdpg        [join]     Software Engineer, Centre of Data for Public Good
2021     cdpg        [ship]     IUDX Adaptor Framework on Flink, 178 of 435 commits
2022-04  cdpg        [promote]  Senior Software Engineer
2022     cdpg        [ship]     IUDX Data Sandbox, 70 of 93 backend commits
2023-04  cdpg        [promote]  Lead Engineer
2023     cdpg        [ship]     ClickHouse analytics: billions of rows, sub-second queries
2024     research    [paper]    LULC segmentation at IEEE InGARSS 2024, plus 2 arXiv papers
2025-08  iisc        [enrol]    Online M.Tech, Data Science and Business Analytics
2025     cdpg        [ship]     Data marketplace file service, 85 of 105 commits
2026     cdpg        [ship]     Multi-kernel notebook images, CPU image 16.1 GB to 8.1 GB
now      cdpg        [running]  Lead Engineer, Bengaluru
```

<details>
<summary><b>Papers</b></summary>
<br/>

- [An Atmospheric Correction Integrated LULC Segmentation Model for High-Resolution Satellite Imagery](https://doi.org/10.1109/InGARSS61818.2024.10984371), IEEE InGARSS 2024
- [Cross Pseudo Supervision Framework for Sparsely Labelled Geospatial Images](https://arxiv.org/abs/2408.02382), arXiv 2024
- [Performance Evaluation of Geospatial Images based on Zarr and Tiff](https://arxiv.org/abs/2411.11291), arXiv 2024
- [Comparison of Segmentation Methods in Remote Sensing for Land Use Land Cover](https://arxiv.org/abs/2507.18099), arXiv 2025

</details>

<details>
<summary><b>At IISc</b></summary>
<br/>

- **Learning What to Remember**: which frames should a vision-language model keep from a long video before it knows the question? The learned memory did not beat the recent-frames baseline, and the report says so.
- **GPT-2 on Mizo**: fine-tuned GPT-2 on a low-resource language, test perplexity 680 to 22.5.

</details>

## fastfetch

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,java,ts,python,nodejs,express,fastapi,graphql&perline=8" alt="Go, Java, TypeScript, Python, Node.js, Express, FastAPI, GraphQL" /><br/>
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,aws,azure,linux,grafana,prometheus,githubactions&perline=8" alt="Kubernetes, Docker, AWS, Azure, Linux, Grafana, Prometheus, GitHub Actions" /><br/>
  <img src="https://skillicons.dev/icons?i=kafka,rabbitmq,postgres,mongodb,redis,angular,react,pytorch&perline=8" alt="Kafka, RabbitMQ, PostgreSQL, MongoDB, Redis, Angular, React, PyTorch" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white" alt="Apache Flink" />
  <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/Ceph-EF5C55?style=flat-square&logo=ceph&logoColor=white" alt="Ceph" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white" alt="MinIO" />
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white" alt="Keycloak" />
  <img src="https://img.shields.io/badge/JupyterHub-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="JupyterHub" />
  <img src="https://img.shields.io/badge/Vert.x-782A90?style=flat-square" alt="Vert.x" />
</p>

## git log --author=swarup

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=swarupe&theme=dark&hide_border=true&background=0D111700&ring=FFB054&fire=FFB054&currStreakLabel=FFB054&sideLabels=E8DCCB&currStreakNum=E8DCCB&sideNums=E8DCCB&dates=A39684&stroke=3A3128&disable_animations=true" />
    <img src="https://streak-stats.demolab.com/?user=swarupe&theme=default&hide_border=true&background=FFFFFF00&ring=B8640F&fire=B8640F&currStreakLabel=B8640F&disable_animations=true" alt="GitHub contribution streak for swarupe" />
  </picture>
</p>

<p align="center">
  <a href="mailto:enamakalswarup@gmail.com"><img src="https://img.shields.io/badge/%24_mutt_--s_hello-enamakalswarup%40gmail.com-ffb054?style=flat-square&labelColor=0b0907" alt="Write to me: enamakalswarup@gmail.com" /></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=110&amp;section=footer&color=0:5a3412%2C45:2a1a0c%2C100:0b0907" />
    <img src="https://capsule-render.vercel.app/api?type=waving&height=110&amp;section=footer&color=0:ffb054,45:f6dcb4,100:fbf3e6" alt="" width="100%" />
  </picture>
</p>
