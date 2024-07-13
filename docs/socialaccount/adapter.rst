Adapter
=======

.. autoclass:: allauth.socialaccount.adapter.DefaultSocialAccountAdapter
   :members:


there is a typo on the 'can_authenticate_by_email(login, email)' explainatoin. 
The first line you add extra 'f' on the 'if':
you type 'Returns True iff authentication by email is active for this login/email.'
