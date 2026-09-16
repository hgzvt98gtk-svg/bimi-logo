# BIMI Logo

An SVG logo prepared for use with **Brand Indicators for Message Identification (BIMI)**.

## Logo

![BIMI logo](logo-bimi.svg)

The source logo is available here:

- [View `logo-bimi.svg`](logo-bimi.svg)
- [Download the raw SVG](https://raw.githubusercontent.com/hgzvt98gtk-svg/bimi-logo/main/logo-bimi.svg)

## Using the logo

1. Confirm that you own or are authorized to use this brand logo.
2. Confirm that the SVG meets the BIMI requirements of your email provider and receiving mail systems.
3. Host the SVG at a stable HTTPS URL.
4. Publish a BIMI DNS record for the sending domain that points to the hosted SVG.

Example record format:

```text
default._bimi.example.com TXT "v=BIMI1; l=https://example.com/path/to/logo-bimi.svg;"
```

Replace `example.com` and the logo URL with your own domain and hosting location. DNS configuration, sender authentication, and certificate requirements may vary by provider. This repository does not provide a BIMI certificate or guarantee mailbox-provider acceptance.

## File requirements

- Keep the logo as a self-contained SVG.
- Serve it over HTTPS.
- Avoid scripts, external resources, and unsupported SVG features.
- Test the final hosted file with a BIMI/SVG validator before publishing it.
- Do not modify the logo unless you have permission from its owner.

## Repository contents

| File | Description |
| --- | --- |
| [`logo-bimi.svg`](logo-bimi.svg) | BIMI logo SVG |

## License and trademark

No license has been granted in this repository unless a separate `LICENSE` file or written agreement says otherwise. The logo may be protected by copyright or trademark rights. Obtain permission from the rights holder before using, modifying, or redistributing it.

## Contributing

Please open an issue before proposing changes to the logo. Any proposed SVG should preserve the logo's appearance and remain compatible with the intended BIMI use case.
