# NAME

Device::LPS331AP - I2C interface to LPS331AP Thermometer and Barometer using Device::SMBus

<div>
    <p>
    <img src="https://img.shields.io/badge/perl-5.10+-brightgreen.svg" alt="Requires Perl 5.10+" />
    <a href="https://travis-ci.org/shantanubhadoria/perl-Device-LPS331AP"><img src="https://api.travis-ci.org/shantanubhadoria/perl-Device-LPS331AP.svg?branch=build/master" alt="Travis status" /></a>
    <a href="http://matrix.cpantesters.org/?dist=Device-LPS331AP%200.006"><img src="https://badgedepot.code301.com/badge/cpantesters/Device-LPS331AP/0.006" alt="CPAN Testers result" /></a>
    <a href="http://cpants.cpanauthors.org/dist/Device-LPS331AP-0.006"><img src="https://badgedepot.code301.com/badge/kwalitee/Device-LPS331AP/0.006" alt="Distribution kwalitee" /></a>
    <a href="https://gratipay.com/shantanubhadoria"><img src="https://img.shields.io/gratipay/shantanubhadoria.svg" alt="Gratipay" /></a>
    </p>
</div>

# VERSION

version 0.006

# ATTRIBUTES

## I2CBusDevicePath

this is the device file path for your I2CBus that the LPS331AP is connected on e.g. /dev/i2c-1
This must be provided during object creation.

## Altimeter

    $self->Altimeter->enable();
    $self->Altimeter->getReading();

This is a object of [Device::Altimeter::LPS331AP](https://metacpan.org/pod/Device::Altimeter::LPS331AP)

# SUPPORT

## Bugs / Feature Requests

Please report any bugs or feature requests through github at 
[https://github.com/shantanubhadoria/perl-device-lps331ap/issues](https://github.com/shantanubhadoria/perl-device-lps331ap/issues).
You will be notified automatically of any progress on your issue.

## Source Code

This is open source software.  The code repository is available for
public review and contribution under the terms of the license.

[https://github.com/shantanubhadoria/perl-device-lps331ap](https://github.com/shantanubhadoria/perl-device-lps331ap)

    git clone git://github.com/shantanubhadoria/perl-device-lps331ap.git

# AUTHOR

Shantanu Bhadoria &lt;shantanu at cpan dott org>

# CONTRIBUTOR

Shantanu <shantanu@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2016 by Shantanu Bhadoria.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
