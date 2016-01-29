# Bootstrap XXS

@author Alexandre Andrieux <aland@smile.fr, alex@icosacid.com>
@since 2016-01-20

Extends Twitter Bootstrap to add a 480px breakpoint
Load it right after bootstrap.css

You can now use new extra classes:
.col-xxs-*, .col-xxs-pull-*, .col-xxs-push-*, .col-xxs-offset-*, .visible-xxs, .hidden-xxs

Note: XS is the base of Bootstrap layout. Rather than overriding the whole grid system, most XXS rules are wrapped in @media queries. Keeps the number of lines low.
