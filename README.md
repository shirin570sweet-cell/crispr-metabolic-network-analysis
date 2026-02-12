# crispr-metabolic-network-analysis
analysis of metabolic networks in CRISPR edited pancreatic cells for diabetes treatment using RNA-seq data. built for NGS portfolio

# CRISPR-Edited Metabolic Network Analysis in Pancreatic-like Cells

پروژه تحلیل شبکه‌های متابولیکی در سلول‌های مدل پانکراس پس از ویرایش ژنتیکی با CRISPR 
(برای درمان دیابت نوع ۲ – تمرکز روی مسیرهای متابولیکی مانند glycolysis و insulin signaling)

## توضیح پروژه
این پروژه بخشی از پورتفولیوی NGS Analyst من است.  
از داده‌های RNA-seq سلول‌های تحت درمان CRISPR (knockout ژن‌های کلیدی متابولیکی) استفاده می‌کنم تا:
- ژن‌های differentially expressed (DE) را شناسایی کنم.
- شبکه‌های متابولیکی (KEGG pathways) قبل و بعد از ویرایش را مقایسه کنم.
- تغییرات در centrality ژن‌ها و مسیرها را تحلیل کنم.

**هدف نهایی**: نشان دادن تأثیر ویرایش ژنتیکی بر شبکه‌های متابولیکی برای کاربردهای درمانی.

## ابزارها و زبان‌ها
- **Python**: Biopython, Pandas, NetworkX, Matplotlib/Seaborn
- **R**: DESeq2 یا edgeR برای differential expression, clusterProfiler یا g:Profiler برای enrichment
- **سایر**: FastQC, HISAT2/STAR, StringTie یا featureCounts, Cytoscape برای visualize شبکه‌ها

## ساختار فولدرها (در حال ساخت)
