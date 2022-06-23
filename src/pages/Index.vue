<template>
  <Directory
    class="narrow dark"
    bgColor="var(--light-blue)"
    bgImage="url('/shapes.svg')"
  >
    <template #page-header>
      <Header class="v3">
        <template>Chris and Sarah</template>
        <template #support>
          <p>This October 1st @ 5:30pm, join us at the Richard's Mosuleum in Oakland Cemetery.</p>
        </template>
      </Header>
    </template>

    <PageSection class="center narrow dark" bgColor="#4190CD">
      <template #title>Don't forget to RSVP</template>
      <template #support>
        <p><a href="/rsvp">Click here &rarr;</a></p>
      </template>
    </PageSection>

    <PageSection class="center dark narrow" bgColor="black">
      <template #title>Parking</template>
      <template #support>
        <p>Parking is available on the west side of the park in front of the entrance.</p>
      </template>

      <Split>
        <template #image>
          <img width="600px" src="/parking.png" />
        </template>
        <template>
          <Card url="https://goo.gl/maps/VFErJtW2ydRskBUE7">
            <template #image>
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d603.0649541439245!2d-84.37585419330597!3d33.74767041499499!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f50395fc25f563%3A0x1fa4623ca2d2985e!2sOakland%20Cemetery%20Parking%20Lot!5e0!3m2!1sen!2sus!4v1655933389048!5m2!1sen!2sus" width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </template>
            <template #label>Event Parking</template>
            <template>Parking</template>
            <template #description>366 M.L.K. Jr Dr SE, Atlanta, GA 30312</template>
          </Card>
        </template>
      </Split>
    </PageSection>

    <PageSection class="center dark narrow" bgColor="#3B84C3">
      <template #title>The Ceremony</template>
      <template #support>
        <p>The ceremony will start at 5:30pm at Richard's Mosuleum within Historic Oakland Cemetery.</p>
      </template>

      <Split>
        <template #image>
          <img width="600px" src="/oakland-cemetery.png" />
          <p>Richard's Mosuleum</p>
        </template>
        <template>
          <Card url="https://goo.gl/maps/RhtFARMd1QGdkrqZ8">
            <template #image>
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3317.469368665513!2d-84.37517838353952!3d33.74853498068942!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f503f2ad1efdcb%3A0x8e89c207b430d2a0!2sOakland%20Cemetery!5e0!3m2!1sen!2sus!4v1655930653802!5m2!1sen!2sus" width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </template>
            <template>Oakland Cemetery</template>
            <template #description>248 Oakland Ave SE, Atlanta, GA 30312</template>
          </Card>
        </template>
      </Split>
    </PageSection>

    <PageSection class="center narrow">

      <template #title>The Reception</template>
      <template #support>
        <p>Elevator Factory is right accross the street from the ceremony. Signs will guide you there.</p>
      </template>

      <Split>
        <template #image>
          <img width="600px" src="/elevator-factory.png" />
        </template>
        <template>
          <Card url="https://g.page/elevatorfactory?share">
            <template #image>
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3317.561701321094!2d-84.37513908353955!3d33.746148180690284!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f503ed7bd46ebf%3A0xb1ad0de1a9a12e02!2sElevator%20Factory%20-%20a%20Shared%20Workspace!5e0!3m2!1sen!2sus!4v1655931085054!5m2!1sen!2sus" width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </template>
            <template>Elevator Factory</template>
            <template #description>437 Memorial Dr SE, Atlanta, GA 30312</template>
          </Card>
        </template>
      </Split>
    </PageSection>
  </Directory>
</template>

<