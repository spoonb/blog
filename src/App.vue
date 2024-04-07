<template>
  <div id="app">
    <Header/>
    <DocList>
      <Doc/>
    </DocList>
    <Navigation>
      <Owner/>
      <DocLink/>
      <LatestDoc/>
      <LatestComment/>
      <Category/>
      <Tag/>
      <Archive/>
      <SiteData/>
    </Navigation>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
import DocList from '@/components/doc/DocList'
import Doc from '@/components/doc/Doc'
import Navigation from '@/components/nav/Navigation'
import Owner from '@/components/nav/Owner'
import DocLink from '@/components/nav/DocLink'
import LatestDoc from '@/components/nav/LatestDoc'
import LatestComment from '@/components/nav/LatestComment'
import Category from '@/components/nav/Category'
import Tag from '@/components/nav/Tag'
import Archive from '@/components/nav/Archive'
import SiteData from '@/components/nav/SiteData'

export default {
  name: 'App',
  components: {
    // header footer moduel
    Header, Footer,
    // document moduel
    DocList, Doc,
    // navigation moduel
    Navigation, Owner, DocLink, LatestDoc, LatestComment, Category, Tag, Archive, SiteData,
  }
}
</script>

<style>
</style>
