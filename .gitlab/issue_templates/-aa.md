I report this [Tracking][catinfo] related domain to be added into the [MyPDNS RPZ Firewall][mpdrf]

```

```

- [X] Wildcarded
- [ ] Individual domain blocking

## RPZ (Response Policy Zone) Rules

```css
domain_name_here   CNAME . ; Tracking
*.domain_name_here   CNAME . ; Tracking
```

### Additional requirements for

#### [hosts] and [Pi-hole]

```css

```

```css
- www
```

#### Adblocker
<details><summary>Click to expand</summary>

```css
N/A
```

</details>

## Screenshots
N/P

## Comments


## My Privacy DNS issues
- `` #

## External sources


### All Submissions:
- [X] Have you followed the guidelines in our [Contributing](CONTRIBUTING.md) document?
- [X] Have you checked to ensure there aren't other open [Merge Requests (MR)][MR] or [issue] for the same update/change?
- [X] Have you added an explanation of what your submission do and why you'd like us to include them??
- [ ] Added [screenshot] for prove of [False Negative][FN]

### Testing face
- [X] Checked the internet for verification?
- [X] Have you successfully ran tests with your changes locally?

### Todo
- [X] RPZ Server
- [X] Added to Source file

#### Logger output

<details><summary>3rd party Domains</summary>

```css
N/A
```

</details>

[catinfo]: https://mypdns.org/mypdns/support/-/wikis/Categories/Trackware
[FN]: https://mypdns.org/MypDNS/support/-/wikis/False-Negative "About False Positive"
[hosts]: https://mypdns.org/mypdns/support/-/wikis/dns/DnsHosts "Hosts files a outdated blacklist format"
[issue]: https://mypdns.org/my-privacy-dns/matrix/-/issues "My Privacy DNS Domain records"
[mpdrf]: https://mypdns.org/my-privacy-dns/matrix/ "My Privacy DNS RPZ Firewall Filter"
[MR]: https://mypdns.org/my-privacy-dns/matrix/-/merge_requests "My Privacy DNS Merge Requests"
[Pi-hole]: https://mypdns.org/my-privacy-dns/matrix/-/blob/master/source/porn_filters/README.md#pi-hole "What is Pi-hole and it limitations"
[screenshot]: https://mypdns.org/MypDNS/support/-/wikis/Screenshot "What is a screenshot"

/label ~Tracking

/weight 8

/publish

/severity critical

/health_status at_risk

/relate #3059
