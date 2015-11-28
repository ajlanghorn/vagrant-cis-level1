# vagrant-ubuntu-cis-level1

This project is aimed to provide an Ubuntu image for use with Vagrant and
both VirtualBox and VMware Fusion. Where possible, it is fully CIS Level 1
compliant. Any anomalies to this are pointed out [below](#nonconformance).

## Usage

Depending on your outcomes, there are a number of ways of using these
images. You can:

  - use the image generated from this repository by Atlas
  - fork this image and build it on your own CI server
  - fork this image and make organisation-specific changes to the fork

If you wish to use the generated image from [Atlas](https://atlas.hashicorp.com), add the following as the value of `config.vm.box` in your Vagrantfile:

  ```
  ajlanghorn/cis-level1
  ```

If you're building this on a different account, or outside of Atlas, the
value - and the keys - you need to provide to the Vagrantfile will change.
At this point, you're best looking at the Vagrant documentation for
assistance.

## Issues

Found a bug? Something gone awry? No fret. Pop an issue in through GitHub,
and I'll pick it up as soon as I can do. Bonus points for raising an issue,
then fixing it with a pull request!

## Contributing

Pull requests are very much welcome, and indeed encouraged. If you're not
sure how to do something or would like feedback, please ask! The best way to
make a pull request that will get merged is to:

  1. Fork this repository
  2. Make your changes, and commit them to a branch on your fork
  3. Open a pull request for that branch to this repository
 
Please note that I do love a good commit message, so any commits made should
have a descriptive yet concise subject, and a descriptive body.
