sa-kong
=======

[![Build Status](https://travis-ci.org/softasap/sa-docker-projectatomic.svg?branch=master)](https://travis-ci.org/softasap/sa-docker-projectatomic)



```yaml
  roles:
    - {
        role: "sa-docker-projectatomic",
        option_buildah: true,
        option_kompose: true,
        option_skopeo: true,
        option_atomic_cli: true
      }
```

Advanced:

```yaml
  roles:
    - {
        role: "sa-docker-projectatomic",
        option_buildah: true,
        option_kompose: true,
        option_skopeo: true,
        option_atomic_cli: true,
        kompose_version: "1.9.0"
      }
```



Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-docker-projectatomic  role using the command


`
   ansible-galaxy install softasap.sa-docker-projectatomic
`

the role will be available in the folder library/sa-docker-projectatomic

Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-docker-projectatomic"
       }

```



Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html
