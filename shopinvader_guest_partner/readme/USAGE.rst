The following methods are added to ``res.partner``:

create_guest_partner()

  Create a new guest partner and set the ``shopinvader-guest`` cookie. Return the newly
  created partner record.

get_guest_partner()

  Return the partner record corresponding to the ``shopinvader-guest`` cookie in the
  current request, if any.
