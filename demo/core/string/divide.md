## String#divide

    require 'facets/string/divide'

    s = "<p>This<b>is</b>a test.</p>"
    d = s.divide(/<.*?>/)
    e = ["<p>This", "<b>is", "</b>a test.", "</p>"]
    d.assert == e

