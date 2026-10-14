# Benchmark mapping
OWASP/LLM findings from BENCH.json; ML-TRL: N/A (not an ML model).
```json
{
  "schema": "anticloud.tier-bench/1",
  "project": "EXIV2",
  "source": {
    "repo_path": "E:\\fenta\\Downloads\\The Anticloud\\ANTICLOUD_REPOS\\CAMERAS\\EXIV2\\UPSTREAM_CLONE",
    "git": {
      "head": "",
      "url": "https://github.com/the-anticloud/OPENMRS_CORE.git",
      "branch": "master",
      "committed_at": "2026-09-29T11:06:59+04:00"
    }
  },
  "metrics": {
    "files_total": 14,
    "source_files_scanned": 4,
    "lines_of_code": 707,
    "languages": {
      "(none)": 3,
      ".js": 3,
      ".jpg": 2,
      ".yml": 1,
      ".gyp": 1,
      ".cc": 1,
      ".json": 1,
      ".md": 1,
      ".opts": 1
    }
  },
  "licence": {
    "spdx": "MIT",
    "class": "A",
    "source_file": "LICENSE",
    "redistribution_allowed": true
  },
  "dependencies": {
    "count": 3,
    "unique": 3,
    "by_ecosystem": {
      "npm": 3
    },
    "list": [
      {
        "ecosystem": "npm",
        "name": "nan",
        "version": "~2.2",
        "source_file": "package.json",
        "raw": ""
      },
      {
        "ecosystem": "npm",
        "name": "should",
        "version": "*",
        "source_file": "package.json",
        "raw": ""
      },
      {
        "ecosystem": "npm",
        "name": "mocha",
        "version": "*",
        "source_file": "package.json",
        "raw": ""
      }
    ]
  },
  "owasp_top10": {
    "total_findings": 1,
    "files_with_findings": 1,
    "severity": {
      "high": 0,
      "medium": 0,
      "low": 1
    },
    "categories": {
      "A01-BrokenAccessControl": {
        "count": 0,
        "findings": []
      },
      "A02-CryptographicFailures": {
        "count": 0,
        "findings": []
      },
      "A03-Injection": {
        "count": 0,
        "findings": []
      },
      "A04-InsecureDesign": {
        "count": 0,
        "findings": []
      },
      "A05-SecurityMisconfiguration": {
        "count": 0,
        "findings": []
      },
      "A06-VulnerableComponents": {
        "count": 0,
        "findings": []
      },
      "A07-AuthFailures": {
        "count": 0,
        "findings": []
      },
      "A08-SoftwareDataIntegrity": {
        "count": 1,
        "findings": [
          {
            "severity": "low",
            "file": "exiv2.js",
            "line": 13,
            "cwe": "CWE-319",
            "snippet": "* 'Exif.Photo.SubSecTimeOriginal', if it exists. See http://exiv2.org/tags.html"
          }
        ]
      },
      "A09-LoggingMonitoringFailures": {
        "count": 0,
        "findings": []
      },
      "A10-SSRF": {
        "count": 0,
        "findings": []
      }
    }
  },
  "owasp_llm_top10": {
    "total_findings": 0,
    "files_with_findings": 0,
    "severity": {
      "high": 0,
      "medium": 0,
      "low": 0
    },
    "categories": {
      "LLM01-PromptInjection": {
        "count": 0,
        "findings": []
      },
      "LLM02-Sensiti
```
