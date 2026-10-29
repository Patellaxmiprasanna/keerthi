pipeline{
  agent any
  stages{
    stage(build and test)
    {
      echo("successful build and test")
    }
  }
  stage(release)
  {
    echo("successful release")
  }
}
stage(monitor)
{
  echo("successful monitor")
}
}
}
post
{
  successful
  {
    echo("successful completed")
  }
}
