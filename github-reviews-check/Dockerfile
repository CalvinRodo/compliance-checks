FROM scratch
ENV ORIGIN = 'cdssnc/github-reviews-check-compliance:latest'
ENV COMPONENT = 'Infrastructure'
ENV DESCRIPTION = 'The GitHub repo shows pull requests with reviews.'
ENV SATISFIES = 'SA-11 (4)'
ENV REPO_URL = 'https://github.com/cds-snc/vac-benefits-directory'
ADD main /
CMD ["/main"]
