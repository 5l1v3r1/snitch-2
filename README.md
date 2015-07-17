# snitch
Usage: snitch.py [options]

Options:

  -h, --help            show this help message and exit
  -U [url], --url=[url]
                        domain(s) or domain extension(s) separated by comma*
  -D [type], --dork=[type]
                        dork type(s) separated by comma*
  -C [dork], --custom=[dork]
                        custom dork*
  -O [file], --output=[file]
                        output file
  -S [ip:port], --socks=[ip:port]
                        socks5 proxy
  -I [seconds], --interval=[seconds]
                        interval between requests, 2s by default
  -P [pages], --pages=[pages]
                        pages to retrieve, 10 by default
  -v                    turn on verbosity


 Dork types:

      info   Information leak & Potential web bugs
      ext    Sensitive extensions
      docs   Documents & Messages
      files  Files & Directories
      soft   Web software
      all    All
