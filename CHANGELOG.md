### v0.2.0 - Refactor data handling, add caching, and update the UI app

- Represent datasets and encoders as classes rather than loose collections of `dict`s
- Make autoencoders optional, i.e., some tracks might be encodable and thus searchable but the encoding might not be decodable.
- Cache chunked, encoded, and autoencoded data as HDF5 files to avoid having to hold everything in memory.
- Update the UI to the latest version of HiGlassApp
- Remove Bootstrap v3, which is used by HiGlass's view header, as it's not needed and imposes a security risk

### v0.1.0 - Initial release

- Search across a single bigWig datasets over up to a few chromosomes